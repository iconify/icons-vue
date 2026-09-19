<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k50q2o0qw.css';
import '../../css/v/vbawtkbgj.css';
import '../../css/b/bv_94_gsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer k50q2o0qw"/><path class="duoicon-primary-layer vbawtkbgj"/><path class="bv_94_gsh duoicon-secondary-layer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:box-2" /></template>
