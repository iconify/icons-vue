<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfja0szta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rfja0szta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:face-laugh-beam" /></template>
