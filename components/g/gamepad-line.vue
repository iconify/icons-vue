<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlq4g3q-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlq4g3q-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:gamepad-line" /></template>
