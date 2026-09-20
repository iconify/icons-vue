<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_jalmbdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j_jalmbdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:dial-pad-finger-2" /></template>
