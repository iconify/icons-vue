<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mih6ygbhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mih6ygbhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:confused-fill" /></template>
