<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7ufp8b5m.css';
import '../../css/c/c98at3bul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7ufp8b5m"/><path class="c98at3bul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:caret-down-square" /></template>
