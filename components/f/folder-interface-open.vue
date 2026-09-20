<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps-bh4bky.css';
import '../../css/b/bey54-03p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ps-bh4bky"/><path class="bey54-03p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-interface-open" /></template>
