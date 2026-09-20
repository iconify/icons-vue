<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8fay54xn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8fay54xn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:loader" /></template>
