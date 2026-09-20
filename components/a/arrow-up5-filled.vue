<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wugwonb5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wugwonb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-up5-filled" /></template>
