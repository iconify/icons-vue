<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyu8dvsvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="hyu8dvsvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:ferry-11" /></template>
