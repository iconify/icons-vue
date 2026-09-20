<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/raytajbvb.css';
import '../../css/s/sez2fgw8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="raytajbvb"/><path class="sez2fgw8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:book-open-bookmark-bold" /></template>
