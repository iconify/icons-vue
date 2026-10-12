<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx1s_uslx.css';
import '../../css/w/w7l0nbbco.css';
import '../../css/y/yl6s3kuad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dx1s_uslx"/><path class="w7l0nbbco"/><path class="yl6s3kuad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:house-cog-filled" /></template>
