<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zasjcbc-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zasjcbc-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:arrow-down-fill" /></template>
