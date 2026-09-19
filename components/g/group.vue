<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc4yxhbiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":819,"height":638};
const content = `<path class="vc4yxhbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:group" /></template>
