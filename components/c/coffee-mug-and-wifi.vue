<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wg-sms8br.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wg-sms8br"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:coffee-mug-and-wifi" /></template>
