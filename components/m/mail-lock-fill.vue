<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkw7-5bhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkw7-5bhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mail-lock-fill" /></template>
