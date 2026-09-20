<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tisl7lofk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tisl7lofk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:board-bus" /></template>
