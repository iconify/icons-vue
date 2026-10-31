<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im0xc24va.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="im0xc24va"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:chevron-left-right-20-solid" /></template>
