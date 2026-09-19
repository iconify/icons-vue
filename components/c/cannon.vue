<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqbk1mbcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":768};
const content = `<path class="qqbk1mbcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:cannon" /></template>
