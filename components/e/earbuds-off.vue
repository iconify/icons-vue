<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y51rkfblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y51rkfblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:earbuds-off" /></template>
