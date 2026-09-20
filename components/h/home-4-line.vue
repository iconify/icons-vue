<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyq8pmbcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tyq8pmbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:home-4-line" /></template>
