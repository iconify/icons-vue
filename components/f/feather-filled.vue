<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj0ua5bzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tj0ua5bzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:feather-filled" /></template>
