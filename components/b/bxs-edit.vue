<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8iq1nhqs.css';
import '../../css/u/upas56-sd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8iq1nhqs"/><path class="upas56-sd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-edit" /></template>
