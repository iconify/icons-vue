<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfd9kegje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfd9kegje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:less-than-equal-filled" /></template>
