<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ioa832b5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ioa832b5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:credly" /></template>
