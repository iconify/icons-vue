<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l31xxeblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l31xxeblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:fast-forward" /></template>
