<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pk5tax74a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pk5tax74a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:loader-2-fill" /></template>
