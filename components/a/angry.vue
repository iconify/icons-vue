<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-xk_ruej.css';
import '../../css/j/jv463gbdf.css';
import '../../css/b/b49q-0sop.css';
import '../../css/s/s3ioz5cym.css';
import '../../css/n/nndxyclzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k-xk_ruej"/><path class="jv463gbdf"/><path class="b49q-0sop"/><path class="s3ioz5cym"/><path class="nndxyclzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:angry" /></template>
