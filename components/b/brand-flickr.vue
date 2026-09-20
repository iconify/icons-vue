<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpz77_b4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpz77_b4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-flickr" /></template>
