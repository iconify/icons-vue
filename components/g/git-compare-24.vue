<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwvqjfwul.css';
import '../../css/h/he6gs9bkw.css';
import '../../css/p/prs_noded.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwvqjfwul"/><path class="he6gs9bkw"/><path class="prs_noded"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:git-compare-24" /></template>
