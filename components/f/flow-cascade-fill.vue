<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohx0-hb1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohx0-hb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:flow-cascade-fill" /></template>
