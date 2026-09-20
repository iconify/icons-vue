<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spmf_h7bn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spmf_h7bn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:inductive-automation" /></template>
