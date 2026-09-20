<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/teh5i7b0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="teh5i7b0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arch" /></template>
