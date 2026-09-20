<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssgx6jbou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ssgx6jbou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:border-right-fill" /></template>
