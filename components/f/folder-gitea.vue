<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xonpi7osi.css';
import '../../css/i/ib8s1i8wi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xonpi7osi"/><path class="ib8s1i8wi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-gitea" /></template>
