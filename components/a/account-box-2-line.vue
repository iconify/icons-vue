<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izjb9cb5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izjb9cb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:account-box-2-line" /></template>
