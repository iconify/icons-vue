<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psyirgjci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psyirgjci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bone" /></template>
