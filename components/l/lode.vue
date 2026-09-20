<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw28ws39f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw28ws39f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:lode" /></template>
