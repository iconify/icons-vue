<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8nwzebsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8nwzebsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flask-round-bottom-outline" /></template>
