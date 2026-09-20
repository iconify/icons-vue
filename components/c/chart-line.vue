<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbbu5e-zd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbbu5e-zd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:chart-line" /></template>
