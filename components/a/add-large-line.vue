<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za1mhnb4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="za1mhnb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:add-large-line" /></template>
