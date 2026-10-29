<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwq5c0b-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwq5c0b-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-penguin-solid" /></template>
