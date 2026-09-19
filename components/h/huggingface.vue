<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3gqadqms.css';
import '../../css/x/x1cgi72hj.css';
import '../../css/b/bp6uewcuv.css';
import '../../css/o/o-yxj2bfk.css';
import '../../css/a/adbgsmbxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="t3gqadqms"/><path class="x1cgi72hj"/><path clip-rule="evenodd" class="bp6uewcuv"/><path clip-rule="evenodd" class="o-yxj2bfk"/><path class="adbgsmbxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:huggingface" /></template>
