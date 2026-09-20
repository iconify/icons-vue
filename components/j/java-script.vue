<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtglbsc1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtglbsc1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:java-script" /></template>
