<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/d/dn5myfbwf.css';
import '../../css/c/ca5a0rbuv.css';
import '../../css/s/sltux9jbj.css';
import '../../css/s/s-dq4inme.css';
import '../../css/s/sij6f2sib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="dn5myfbwf"/><path class="ca5a0rbuv"/><path class="sltux9jbj"/><path class="s-dq4inme"/><path class="sij6f2sib"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:cloud-spanner" /></template>
