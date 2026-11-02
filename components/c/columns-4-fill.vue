<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgs_ek1rs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgs_ek1rs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:columns-4-fill" /></template>
