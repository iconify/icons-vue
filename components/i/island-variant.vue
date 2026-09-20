<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_svf083s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_svf083s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:island-variant" /></template>
