<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bddobsb4k.css';
import '../../css/j/jl2yhkqww.css';
import '../../css/b/btg3-9-vx.css';
import '../../css/q/qglkbnbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bddobsb4k"/><path class="jl2yhkqww"/><path class="btg3-9-vx"/><path class="qglkbnbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:copilot" /></template>
