<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8gjv4ccw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y8gjv4ccw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cart-3-bold" /></template>
