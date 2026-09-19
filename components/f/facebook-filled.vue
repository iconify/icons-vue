<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw7-gdcrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vw7-gdcrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:facebook-filled" /></template>
