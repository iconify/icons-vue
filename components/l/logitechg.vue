<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wozos1b-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wozos1b-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:logitechg" /></template>
