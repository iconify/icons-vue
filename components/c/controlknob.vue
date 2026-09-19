<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrmchxbkx.css';
import '../../css/c/ct8h_-63x.css';
import '../../css/i/ix-wrkbcl.css';
import '../../css/g/gt8_c-sxg.css';
import '../../css/n/nvux4rq-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zrmchxbkx"/><path class="ct8h_-63x"/><path class="ix-wrkbcl"/><path class="gt8_c-sxg"/><path class="nvux4rq-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:controlknob" /></template>
