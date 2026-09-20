<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_b2hwbyf.css';
import '../../css/o/oj5wobigx.css';
import '../../css/r/r5bozrdyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_b2hwbyf"/><path class="oj5wobigx"/><path class="r5bozrdyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:hospital" /></template>
