<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gm1n6kb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gm1n6kb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:equals" /></template>
