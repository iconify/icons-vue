<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgvrc_86n.css';
import '../../css/k/knx35mxfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgvrc_86n"/><path class="knx35mxfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:donate-heart" /></template>
