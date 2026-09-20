<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fytd5lhkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fytd5lhkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:blood-alert-outline" /></template>
