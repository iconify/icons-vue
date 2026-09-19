<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox_ew8r3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ox_ew8r3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:balloon-filled" /></template>
