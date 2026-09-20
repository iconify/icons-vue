<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/om5-2ls3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="om5-2ls3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:cloud-off-line" /></template>
