<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5aa9x36e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5aa9x36e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:bank-card-2-fill" /></template>
