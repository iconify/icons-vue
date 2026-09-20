<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwh7egbqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwh7egbqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:dumbbell" /></template>
