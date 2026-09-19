<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbyzct5is.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1023};
const content = `<path class="xbyzct5is"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:day" /></template>
