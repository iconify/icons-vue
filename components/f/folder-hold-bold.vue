<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-cra3-wf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-cra3-wf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:folder-hold-bold" /></template>
