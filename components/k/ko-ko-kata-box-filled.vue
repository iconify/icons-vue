<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xy2jglbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xy2jglbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:ko-ko-kata-box-filled" /></template>
