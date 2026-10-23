<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgptf3xic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgptf3xic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:chef-hat" /></template>
