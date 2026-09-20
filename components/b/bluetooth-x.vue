<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ix4mo_g6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ix4mo_g6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bluetooth-x" /></template>
