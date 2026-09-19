<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zd5y7vbjg.css';
import '../../css/x/x5qxkepnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zd5y7vbjg"/><path class="x5qxkepnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:dvd-logo" /></template>
