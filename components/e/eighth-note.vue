<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a44g3_ugi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a44g3_ugi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:eighth-note" /></template>
