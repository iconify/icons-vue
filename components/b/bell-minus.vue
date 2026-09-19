<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq31b6swd.css';
import '../../css/q/q0seobblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qq31b6swd"/><path class="q0seobblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bell-minus" /></template>
