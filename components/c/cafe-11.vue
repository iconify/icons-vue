<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt5h8wfck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="qt5h8wfck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:cafe-11" /></template>
