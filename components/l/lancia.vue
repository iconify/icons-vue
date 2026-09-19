<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnas58u_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnas58u_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:lancia" /></template>
