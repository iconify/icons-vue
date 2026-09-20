<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tphv1z1vt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tphv1z1vt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:high-temperature-fill" /></template>
