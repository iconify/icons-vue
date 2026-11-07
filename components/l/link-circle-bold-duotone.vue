<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg928d-qd.css';
import '../../css/u/u2anyn4fc.css';
import '../../css/b/bbs3bcbxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vg928d-qd"/><path class="u2anyn4fc"/><path class="bbs3bcbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:link-circle-bold-duotone" /></template>
