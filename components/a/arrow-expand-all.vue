<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_rw8yb_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_rw8yb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-expand-all" /></template>
