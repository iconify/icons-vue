<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agwbi96kj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agwbi96kj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:building-office-2" /></template>
