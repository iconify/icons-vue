<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpyt5qnqj.css';
import '../../css/o/oaj_2iwov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dpyt5qnqj"/><path class="oaj_2iwov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:hand-three-finger" /></template>
