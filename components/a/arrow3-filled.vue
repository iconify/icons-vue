<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obavzobga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obavzobga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow3-filled" /></template>
