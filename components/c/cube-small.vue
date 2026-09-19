<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz1gjqb4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="vz1gjqb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:cube-small" /></template>
