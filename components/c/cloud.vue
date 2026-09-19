<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osn1-qbmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="osn1-qbmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:cloud" /></template>
