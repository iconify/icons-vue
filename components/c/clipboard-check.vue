<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngxvv9bnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngxvv9bnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:clipboard-check" /></template>
