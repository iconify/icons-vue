<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcr-_t1sf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcr-_t1sf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ease-out-control-point" /></template>
