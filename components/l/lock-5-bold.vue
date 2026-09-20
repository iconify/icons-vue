<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/so7wwzbyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="so7wwzbyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:lock-5-bold" /></template>
