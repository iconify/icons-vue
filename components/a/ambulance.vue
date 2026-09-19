<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/puty-vbng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="puty-vbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:ambulance" /></template>
