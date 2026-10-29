<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta07lbb5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ta07lbb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:contact-solid" /></template>
