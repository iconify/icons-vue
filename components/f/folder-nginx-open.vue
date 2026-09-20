<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lo_p2j3uc.css';
import '../../css/y/yorsrhfgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lo_p2j3uc"/><path class="yorsrhfgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-nginx-open" /></template>
