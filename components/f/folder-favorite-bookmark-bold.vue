<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_n90ytqs.css';
import '../../css/z/zwya4wbyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_n90ytqs"/><path class="zwya4wbyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-favorite-bookmark-bold" /></template>
