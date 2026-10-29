<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihh9i5bby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihh9i5bby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bamboo-solid" /></template>
