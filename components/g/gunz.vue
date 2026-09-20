<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhmdxdonw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhmdxdonw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:gunz" /></template>
