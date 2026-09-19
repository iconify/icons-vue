<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw_ai_brw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rw_ai_brw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:globe" /></template>
