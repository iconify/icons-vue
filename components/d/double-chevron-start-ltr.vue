<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmjdz1bia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xmjdz1bia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:double-chevron-start-ltr" /></template>
