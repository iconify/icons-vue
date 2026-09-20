<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b559-z69b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b559-z69b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:letter-a-box" /></template>
