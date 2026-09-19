<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx-bmy_tr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="yx-bmy_tr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:angles-up" /></template>
