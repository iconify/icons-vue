<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt6umrt6x.css';
import '../../css/p/p60zoqpev.css';
import '../../css/m/ma9vvmbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qt6umrt6x"/><path class="p60zoqpev"/><path clip-rule="evenodd" class="ma9vvmbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cart-5-outline" /></template>
