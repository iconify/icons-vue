<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exg9pl4_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exg9pl4_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chevron-left-circle-outline" /></template>
