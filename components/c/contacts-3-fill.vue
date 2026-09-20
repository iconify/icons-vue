<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8b5ddb7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8b5ddb7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:contacts-3-fill" /></template>
