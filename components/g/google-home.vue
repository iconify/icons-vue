<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmrft0p9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmrft0p9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:google-home" /></template>
