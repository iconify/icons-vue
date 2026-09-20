<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opj97bpgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="opj97bpgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:discount" /></template>
