<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg0h8xb-u.css';
import '../../css/c/c0keyp4fy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eg0h8xb-u"/><circle class="c0keyp4fy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-game" /></template>
