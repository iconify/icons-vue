<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpgdi0v8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xpgdi0v8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:linkedin-with-circle" /></template>
