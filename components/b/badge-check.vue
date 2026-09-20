<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyl9qceen.css';
import '../../css/k/k02-v4bci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gyl9qceen"/><path class="k02-v4bci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:badge-check" /></template>
