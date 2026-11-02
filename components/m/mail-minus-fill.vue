<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjnsjssld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjnsjssld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mail-minus-fill" /></template>
