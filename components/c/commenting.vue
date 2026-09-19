<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3nbq0pup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1504};
const content = `<path class="u3nbq0pup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:commenting" /></template>
