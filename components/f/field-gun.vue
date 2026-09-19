<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcmit3xpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hcmit3xpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:field-gun" /></template>
