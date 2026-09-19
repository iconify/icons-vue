<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk7j9cb8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rk7j9cb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:console-filled" /></template>
