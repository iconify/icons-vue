<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/meydrebwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="meydrebwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:clever-cloud" /></template>
