<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohq_zrbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ohq_zrbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:lable-fill" /></template>
