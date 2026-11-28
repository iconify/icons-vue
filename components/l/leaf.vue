<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmpytpb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmpytpb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:leaf" /></template>
