<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyf535b2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fyf535b2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:chat" /></template>
