<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clh07fbwo.css';
import '../../css/h/hhq74abkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clh07fbwo"/><rect class="hhq74abkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:horizontal-spacing-filled" /></template>
