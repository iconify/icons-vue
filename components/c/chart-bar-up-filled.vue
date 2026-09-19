<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnt2b8bbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rnt2b8bbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chart-bar-up-filled" /></template>
