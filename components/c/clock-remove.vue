<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a64h9hb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a64h9hb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clock-remove" /></template>
