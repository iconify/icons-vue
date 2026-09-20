<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjp9ywjxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjp9ywjxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:lock-open-alt" /></template>
