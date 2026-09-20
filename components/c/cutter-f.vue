<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo061fb5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-1.5,"top":-1.5};
const content = `<path class="uo061fb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:cutter-f" /></template>
