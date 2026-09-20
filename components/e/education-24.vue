<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7uzulnob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z7uzulnob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:education-24" /></template>
