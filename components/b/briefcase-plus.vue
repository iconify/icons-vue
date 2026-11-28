<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot2v1db-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ot2v1db-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:briefcase-plus" /></template>
