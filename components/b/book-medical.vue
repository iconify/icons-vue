<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vt1kn2zpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="vt1kn2zpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:book-medical" /></template>
