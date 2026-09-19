<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7edix8yx.css';
import '../../css/f/f-emzobbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7edix8yx"/><path class="f-emzobbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:chevrons-down" /></template>
