<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi5uaactm.css';
import '../../css/r/rnzp9jboq.css';
import '../../css/v/vayq6bcaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hi5uaactm"/><path class="rnzp9jboq"/><path class="vayq6bcaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-leak-20" /></template>
