<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oaq99ccvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oaq99ccvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:beaker-empty-alt" /></template>
