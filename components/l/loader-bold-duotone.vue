<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql-1g5bil.css';
import '../../css/w/we5rc8m_b.css';
import '../../css/i/igcg0ebrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ql-1g5bil"/><path class="we5rc8m_b"/><path class="igcg0ebrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:loader-bold-duotone" /></template>
