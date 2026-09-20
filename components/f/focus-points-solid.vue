<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytl2035my.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ytl2035my"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:focus-points-solid" /></template>
