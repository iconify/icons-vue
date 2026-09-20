<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmr7w7n-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="wmr7w7n-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:bolt" /></template>
