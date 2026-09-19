<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx3cjdb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="tx3cjdb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:influxdb" /></template>
