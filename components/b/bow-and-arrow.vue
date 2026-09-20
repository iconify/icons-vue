<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjt728jjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gjt728jjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:bow-and-arrow" /></template>
