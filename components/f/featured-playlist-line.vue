<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq99g-23z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bq99g-23z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:featured-playlist-line" /></template>
