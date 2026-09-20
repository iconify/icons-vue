<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bae35fb2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bae35fb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:git-branch-solid" /></template>
