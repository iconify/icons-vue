<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svb-z_tut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="svb-z_tut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:artstation" /></template>
