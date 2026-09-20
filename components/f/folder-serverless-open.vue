<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixetddbeg.css';
import '../../css/u/ud9xiabyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ixetddbeg"/><path class="ud9xiabyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-serverless-open" /></template>
