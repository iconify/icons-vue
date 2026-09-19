<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3vxumw8s.css';
import '../../css/g/gkjqfnbjw.css';
import '../../css/g/g7isto0zn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="v3vxumw8s"/><path class="gkjqfnbjw"/><path class="g7isto0zn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:container-runtime-monitor" /></template>
