<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4z9h5b-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4z9h5b-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-8-line" /></template>
