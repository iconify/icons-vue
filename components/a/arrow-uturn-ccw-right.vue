<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm9im5b1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qm9im5b1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrow-uturn-ccw-right" /></template>
