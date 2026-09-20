<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5zp4067s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5zp4067s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-letter-ends-with" /></template>
