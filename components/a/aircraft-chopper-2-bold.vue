<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz-uxmbck.css';
import '../../css/r/r8i2-5bdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iz-uxmbck"/><path class="r8i2-5bdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:aircraft-chopper-2-bold" /></template>
