<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1kkvib8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u1kkvib8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:forward2-filled" /></template>
