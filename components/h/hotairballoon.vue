<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0vmx-8pt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":32};
const content = `<path class="k0vmx-8pt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:hotairballoon" /></template>
