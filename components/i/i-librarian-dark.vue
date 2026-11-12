<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxl1morjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wxl1morjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:i-librarian-dark" /></template>
