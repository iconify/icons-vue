<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i37lj7btr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i37lj7btr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:arrow-alt-circle-down" /></template>
