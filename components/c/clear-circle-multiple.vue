<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw0xa2w6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kw0xa2w6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clear-circle-multiple" /></template>
