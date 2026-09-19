<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wslkg7oxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wslkg7oxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:card-sharp" /></template>
