<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_4g8ix3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_4g8ix3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:escalator-filled" /></template>
