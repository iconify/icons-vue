<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_e-c1b-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_e-c1b-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:flag-alt-1-line" /></template>
