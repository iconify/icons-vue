<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikwwh-bte.css';
import '../../css/w/w950tvqcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ikwwh-bte"/><path class="w950tvqcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:fax" /></template>
