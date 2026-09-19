<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glvlf_bmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="glvlf_bmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:france5" /></template>
