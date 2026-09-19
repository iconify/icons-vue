<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f50-edbfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f50-edbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:layout-outline" /></template>
