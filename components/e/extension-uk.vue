<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9aimcb7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9aimcb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:extension-uk" /></template>
