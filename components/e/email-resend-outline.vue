<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdg08x6jc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdg08x6jc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:email-resend-outline" /></template>
