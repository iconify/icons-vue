<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4oss2bsv.css';
import '../../css/h/hkly8r6yp.css';
import '../../css/x/x3tzvpboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4oss2bsv wm-k"/><path class="hkly8r6yp wm-k"/><path class="wm-k x3tzvpboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:bold" /></template>
