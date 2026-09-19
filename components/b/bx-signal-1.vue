<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/useoh5bdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="useoh5bdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-signal-1" /></template>
