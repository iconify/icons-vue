<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx4cobs8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sx4cobs8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:apache-freemarker" /></template>
