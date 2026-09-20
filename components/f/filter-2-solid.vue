<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjgzohr4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wjgzohr4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:filter-2-solid" /></template>
