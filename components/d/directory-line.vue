<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnhtf_fam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cnhtf_fam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:directory-line" /></template>
