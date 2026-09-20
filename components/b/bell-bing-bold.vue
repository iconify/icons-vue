<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha2wewu4o.css';
import '../../css/e/e15g94bve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ha2wewu4o"/><path clip-rule="evenodd" class="e15g94bve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bell-bing-bold" /></template>
