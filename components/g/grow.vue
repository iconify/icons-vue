<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqo-n47ib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="rqo-n47ib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:grow" /></template>
