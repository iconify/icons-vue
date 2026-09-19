<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0n74mbkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="l0n74mbkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:corejs-wordmark" /></template>
