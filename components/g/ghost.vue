<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/f/f7g7vtbvj.css';
import '../../css/p/p21puft2v.css';
import '../../css/e/ehkk3-jzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="f7g7vtbvj"/><path class="p21puft2v"/><path class="ehkk3-jzt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:ghost" /></template>
