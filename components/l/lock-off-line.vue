<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v19d-t26v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v19d-t26v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:lock-off-line" /></template>
