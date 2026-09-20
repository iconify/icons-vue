<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqz_0b6fc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqz_0b6fc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-up-fill" /></template>
