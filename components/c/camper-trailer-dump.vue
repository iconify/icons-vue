<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob72q5bva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ob72q5bva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:camper-trailer-dump" /></template>
