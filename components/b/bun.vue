<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osbm_yzxy.css';
import '../../css/a/ay6sfyn6f.css';
import '../../css/p/pwf6_mkij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="osbm_yzxy"/><path class="ay6sfyn6f"/><path class="pwf6_mkij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:bun" /></template>
