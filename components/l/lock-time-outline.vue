<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kq_7pjv9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kq_7pjv9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:lock-time-outline" /></template>
