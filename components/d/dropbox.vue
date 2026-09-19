<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9ftu10bs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1568};
const content = `<path class="t9ftu10bs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:dropbox" /></template>
