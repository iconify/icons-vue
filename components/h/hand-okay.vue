<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd7x03eky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qd7x03eky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hand-okay" /></template>
