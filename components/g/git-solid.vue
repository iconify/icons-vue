<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/noygarn3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="noygarn3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:git-solid" /></template>
