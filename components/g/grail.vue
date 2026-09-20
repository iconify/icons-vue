<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl2f5eiiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yl2f5eiiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:grail" /></template>
