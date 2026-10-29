<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vub7g5blo.css';
import '../../css/o/oxal30bwl.css';
import '../../css/f/foipgeybq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vub7g5blo wm-k"/><path class="oxal30bwl wm-k"/><path class="foipgeybq wm-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:cloud-off" /></template>
