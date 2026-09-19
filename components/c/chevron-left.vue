<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-9m4gbpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y-9m4gbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:chevron-left" /></template>
