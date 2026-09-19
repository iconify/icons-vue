<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt_uxyb5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pt_uxyb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:battery-slash" /></template>
