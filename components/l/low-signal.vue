<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thluib7ry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thluib7ry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:low-signal" /></template>
