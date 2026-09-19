<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjxrqjgru.css';
import '../../css/a/ads37eh-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjxrqjgru"/><path class="ads37eh-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:archive-alt" /></template>
