<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md-wfsf-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="md-wfsf-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:diskette-outline" /></template>
