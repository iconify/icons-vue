<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbrld-b7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbrld-b7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:arrow-sorted-up" /></template>
