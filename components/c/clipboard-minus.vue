<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibu_r4lcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ibu_r4lcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:clipboard-minus" /></template>
