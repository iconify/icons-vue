<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqhrmjx-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqhrmjx-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-cache-outline" /></template>
