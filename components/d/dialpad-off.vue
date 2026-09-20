<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y86xn6bek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y86xn6bek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:dialpad-off" /></template>
