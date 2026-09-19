<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv15nl59b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="gv15nl59b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:dribble" /></template>
