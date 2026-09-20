<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-vp84b5b.css';
import '../../css/j/jkrx8ppgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-vp84b5b"/><path class="jkrx8ppgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:laptop-clock-bold" /></template>
