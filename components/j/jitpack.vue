<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oihh1ccpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oihh1ccpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:jitpack" /></template>
