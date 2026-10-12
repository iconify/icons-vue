<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lchpdvb_j.css';
import '../../css/s/sigei6ulc.css';
import '../../css/g/g5ucz7ltn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lchpdvb_j"/><path class="sigei6ulc"/><path class="g5ucz7ltn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mail-plus-duotone" /></template>
