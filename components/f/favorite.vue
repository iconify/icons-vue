<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3g3o-fjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3g3o-fjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:favorite" /></template>
