<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk_ma8b9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sk_ma8b9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:lock" /></template>
