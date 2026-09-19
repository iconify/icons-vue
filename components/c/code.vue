<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhq6yjbhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1500,"height":1000};
const content = `<path class="uhq6yjbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:code" /></template>
