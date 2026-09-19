<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eald8w6bs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eald8w6bs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:connectivity-lan-filled" /></template>
