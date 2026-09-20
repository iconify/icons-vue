<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_3_7o6we.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_3_7o6we"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:image-frame" /></template>
