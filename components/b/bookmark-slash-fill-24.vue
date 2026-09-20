<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nq5os2voj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nq5os2voj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:bookmark-slash-fill-24" /></template>
