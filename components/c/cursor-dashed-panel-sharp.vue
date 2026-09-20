<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvbv0eb9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvbv0eb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cursor-dashed-panel-sharp" /></template>
