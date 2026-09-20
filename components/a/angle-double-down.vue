<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhj_kjb2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhj_kjb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:angle-double-down" /></template>
