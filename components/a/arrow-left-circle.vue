<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxdt4rk6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxdt4rk6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:arrow-left-circle" /></template>
