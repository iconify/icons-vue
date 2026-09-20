<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m20ppcu0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m20ppcu0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:battery-low-bold" /></template>
