<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgy4qqb9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgy4qqb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-bar-up" /></template>
