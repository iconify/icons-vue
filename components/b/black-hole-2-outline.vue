<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0udpcchx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g0udpcchx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:black-hole-2-outline" /></template>
