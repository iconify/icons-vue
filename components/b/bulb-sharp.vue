<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhezqac2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dhezqac2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:bulb-sharp" /></template>
