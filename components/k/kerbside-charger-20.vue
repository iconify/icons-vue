<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq9167bja.css';
import '../../css/m/m744oxfrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qq9167bja"/><path class="m744oxfrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:kerbside-charger-20" /></template>
