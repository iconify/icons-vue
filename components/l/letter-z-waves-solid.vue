<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt8h2yaft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gt8h2yaft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-z-waves-solid" /></template>
