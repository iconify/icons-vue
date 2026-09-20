<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kiufbeg5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kiufbeg5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrange-bring-to-front" /></template>
