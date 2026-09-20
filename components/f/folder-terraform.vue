<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6cjc0bct.css';
import '../../css/x/xb829869a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v6cjc0bct"/><path class="xb829869a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-terraform" /></template>
