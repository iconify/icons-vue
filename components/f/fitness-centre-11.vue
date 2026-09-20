<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ne1b9cdgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="ne1b9cdgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:fitness-centre-11" /></template>
