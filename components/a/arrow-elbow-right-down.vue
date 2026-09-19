<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixvq6mbmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ixvq6mbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:arrow-elbow-right-down" /></template>
