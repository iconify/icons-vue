<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2g9ov_6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2g9ov_6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:chevrons-up" /></template>
