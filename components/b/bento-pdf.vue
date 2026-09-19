<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsxfjy2lx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsxfjy2lx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bento-pdf" /></template>
