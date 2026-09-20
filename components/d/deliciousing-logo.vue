<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp8w1geor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pp8w1geor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:deliciousing-logo" /></template>
