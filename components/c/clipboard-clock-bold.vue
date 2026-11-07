<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je9uz5b7m.css';
import '../../css/z/z8_m97b4y.css';
import '../../css/c/c4946-17v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="je9uz5b7m"/><path clip-rule="evenodd" class="z8_m97b4y"/><path class="c4946-17v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clipboard-clock-bold" /></template>
