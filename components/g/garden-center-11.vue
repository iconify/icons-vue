<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opwx81bno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="opwx81bno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:garden-center-11" /></template>
