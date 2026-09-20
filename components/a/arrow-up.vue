<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpsstfvmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpsstfvmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:arrow-up" /></template>
