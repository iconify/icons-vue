<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubgk3rb-x.css';
import '../../css/k/kx15g1jff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubgk3rb-x"/><path clip-rule="evenodd" class="kx15g1jff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ios-fill" /></template>
