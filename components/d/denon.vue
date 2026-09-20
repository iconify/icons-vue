<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztey5v61a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztey5v61a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:denon" /></template>
