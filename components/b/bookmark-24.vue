<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9gx19_go.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9gx19_go"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:bookmark-24" /></template>
