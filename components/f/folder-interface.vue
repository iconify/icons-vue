<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch5-wbctd.css';
import '../../css/b/bey54-03p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ch5-wbctd"/><path class="bey54-03p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-interface" /></template>
