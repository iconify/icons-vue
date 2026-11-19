<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7w0j0b5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7w0j0b5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:desklamp" /></template>
