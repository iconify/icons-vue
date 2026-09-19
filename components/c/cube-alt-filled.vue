<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shwe8vnzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="shwe8vnzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:cube-alt-filled" /></template>
