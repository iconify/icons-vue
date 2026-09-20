<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm4hm_17s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vm4hm_17s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:list-indent-decrease" /></template>
