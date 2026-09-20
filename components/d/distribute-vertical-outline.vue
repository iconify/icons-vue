<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb8_5bccr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lb8_5bccr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:distribute-vertical-outline" /></template>
