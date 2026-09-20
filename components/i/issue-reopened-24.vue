<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a804f_bji.css';
import '../../css/v/v5yyqhbqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a804f_bji"/><path class="v5yyqhbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:issue-reopened-24" /></template>
