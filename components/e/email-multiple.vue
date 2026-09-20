<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/m/mi5qmx.css';
import '../../css/z/z4421m.css';
import '../../css/z/z-3bwb.css';
import '../../css/s/so-from-66.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c mi5qmx"/><path class="a0m25c z4421m"/><path class="a0m25c z-3bwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:email-multiple" /></template>
