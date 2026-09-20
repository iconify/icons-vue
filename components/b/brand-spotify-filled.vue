<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6q_tob7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6q_tob7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-spotify-filled" /></template>
