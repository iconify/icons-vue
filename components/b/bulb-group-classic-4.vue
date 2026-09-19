<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5glx5ber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5glx5ber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bulb-group-classic-4" /></template>
