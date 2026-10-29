<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_4s8bbrt.css';
import '../../css/e/e_hcxgbui.css';
import '../../css/q/q-_fprbsy.css';
import '../../css/a/aepnqsb1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_4s8bbrt wm-k"/><path class="e_hcxgbui wm-a"/><path class="q-_fprbsy wm-k"/><path class="aepnqsb1e wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:lightbulb" /></template>
