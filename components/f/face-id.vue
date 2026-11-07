<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbotjw3iw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbotjw3iw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:face-id" /></template>
