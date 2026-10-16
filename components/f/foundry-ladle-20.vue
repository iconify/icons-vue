<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3j2ttbri.css';
import '../../css/w/w0ahlnbjy.css';
import '../../css/p/pycxazbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o3j2ttbri"/><path class="w0ahlnbjy"/><path class="pycxazbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:foundry-ladle-20" /></template>
