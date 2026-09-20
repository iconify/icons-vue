<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwkw_ebhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zwkw_ebhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:git-fork-outline" /></template>
