<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hig03zb4r.css';
import '../../css/g/g0dn0ibjz.css';
import '../../css/s/slpchx0bj.css';
import '../../css/u/uw4yw0awk.css';
import '../../css/t/t74sydbxp.css';
import '../../css/c/cglbq3bnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hig03zb4r"/><path clip-rule="evenodd" class="g0dn0ibjz"/><path class="slpchx0bj"/><path class="uw4yw0awk"/><path class="t74sydbxp"/><path class="cglbq3bnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hand-money-bold" /></template>
