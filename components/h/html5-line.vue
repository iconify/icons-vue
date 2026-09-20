<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/helu_3bmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="helu_3bmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:html5-line" /></template>
