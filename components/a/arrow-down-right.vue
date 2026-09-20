<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9n22k39k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9n22k39k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:arrow-down-right" /></template>
