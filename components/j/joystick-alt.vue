<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryk7c9tyn.css';
import '../../css/r/rv64cqbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryk7c9tyn"/><path class="rv64cqbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:joystick-alt" /></template>
