<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7_c5ho3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7_c5ho3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-credit-card" /></template>
