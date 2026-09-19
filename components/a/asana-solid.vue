<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oiq2jf6xu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oiq2jf6xu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:asana-solid" /></template>
