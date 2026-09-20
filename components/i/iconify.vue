<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n00ht3k3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n00ht3k3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:iconify" /></template>
