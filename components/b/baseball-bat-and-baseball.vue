<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjbo7ppxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pjbo7ppxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:baseball-bat-and-baseball" /></template>
