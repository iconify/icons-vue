<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_-aeeb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_-aeeb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:corner-up-left" /></template>
