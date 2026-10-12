<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz3abnbbb.css';
import '../../css/y/y1iswdb7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gz3abnbbb"/><path class="y1iswdb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cookie-filled" /></template>
