<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz98m2akc.css';
import '../../css/k/kbbue1bxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mz98m2akc"/><path class="kbbue1bxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:bus-sharp" /></template>
