<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/bg26ztbll.css';
import '../../css/i/if7b_fg1p.css';
import '../../css/v/vcufaui4b.css';
import '../../css/d/dm7s30bzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bg26ztbll"/><path class="if7b_fg1p"/><path class="vcufaui4b"/><path class="dm7s30bzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:git-branch-line-duotone" /></template>
