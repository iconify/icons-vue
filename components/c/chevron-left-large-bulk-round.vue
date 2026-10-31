<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hr3-7w_6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hr3-7w_6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chevron-left-large-bulk-round" /></template>
