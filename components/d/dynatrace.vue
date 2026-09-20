<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md2xcdxyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="md2xcdxyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:dynatrace" /></template>
