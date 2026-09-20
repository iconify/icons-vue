<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkzbi_b2t.css';
import '../../css/k/ki5l85g2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkzbi_b2t"/><path class="ki5l85g2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:check-square" /></template>
