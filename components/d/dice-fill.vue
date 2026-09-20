<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-4swvbdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-4swvbdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:dice-fill" /></template>
