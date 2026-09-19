<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abtk0lbbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abtk0lbbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:google-drive" /></template>
