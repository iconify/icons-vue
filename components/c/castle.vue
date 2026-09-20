<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llez85_pb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="llez85_pb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:castle" /></template>
