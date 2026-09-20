<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co4u79bom.css';
import '../../css/t/t_qykii2y.css';
import '../../css/b/b6znd0b_r.css';
import '../../css/d/dgcljpugd.css';
import '../../css/g/gt-o6rbgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<rect class="co4u79bom"/><rect class="t_qykii2y"/><circle class="b6znd0b_r"/><circle class="dgcljpugd"/><rect class="gt-o6rbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:coloredpetrinets" /></template>
