<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi3eqrf6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oi3eqrf6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:clubs-02" /></template>
