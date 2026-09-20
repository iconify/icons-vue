<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npiotbeyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npiotbeyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:credit-card-minus" /></template>
