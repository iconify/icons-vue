<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzxcdvb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jzxcdvb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:chevron-left" /></template>
