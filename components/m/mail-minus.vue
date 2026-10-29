<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr6h8emnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gr6h8emnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:mail-minus" /></template>
