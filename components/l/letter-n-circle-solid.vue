<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttqu9ibyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttqu9ibyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-n-circle-solid" /></template>
