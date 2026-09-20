<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_4wmij0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":300};
const content = `<path class="b_4wmij0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:helm" /></template>
