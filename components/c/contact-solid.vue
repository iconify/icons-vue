<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkvilf07h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkvilf07h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:contact-solid" /></template>
