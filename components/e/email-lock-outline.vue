<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jh4qz-4wq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jh4qz-4wq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:email-lock-outline" /></template>
