<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6i8fxkqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6i8fxkqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:friends-of-hue-marbul-suspended" /></template>
