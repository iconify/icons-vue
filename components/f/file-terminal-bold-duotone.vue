<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj6gwrmjs.css';
import '../../css/f/ffwd6obzr.css';
import '../../css/o/o0qlb2nqx.css';
import '../../css/q/q2ycdab-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oj6gwrmjs"/><path class="ffwd6obzr"/><path class="o0qlb2nqx"/><path class="q2ycdab-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-terminal-bold-duotone" /></template>
