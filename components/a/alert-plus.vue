<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_3zf4ikc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_3zf4ikc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alert-plus" /></template>
