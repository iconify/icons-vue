<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp1ly_bxy.css';
import '../../css/t/tuvamblkg.css';
import '../../css/i/i1958g00u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mp1ly_bxy"/><rect class="tuvamblkg"/><path class="i1958g00u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:document-layout-right" /></template>
