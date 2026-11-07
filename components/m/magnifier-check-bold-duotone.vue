<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwqarthoa.css';
import '../../css/f/frxk7_buw.css';
import '../../css/y/yrnx5ea_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwqarthoa"/><path class="frxk7_buw"/><path class="yrnx5ea_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magnifier-check-bold-duotone" /></template>
