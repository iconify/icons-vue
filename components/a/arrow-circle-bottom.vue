<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6q-f6bnh.css';
import '../../css/m/m2i_l4b6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r6q-f6bnh"/><path class="m2i_l4b6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:arrow-circle-bottom" /></template>
