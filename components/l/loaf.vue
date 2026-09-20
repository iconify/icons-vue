<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9ce1qk7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9ce1qk7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:loaf" /></template>
