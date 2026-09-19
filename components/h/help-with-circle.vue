<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkved2b9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gkved2b9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:help-with-circle" /></template>
