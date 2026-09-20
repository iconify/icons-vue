<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsyn_yf4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsyn_yf4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:comment-bookmark" /></template>
