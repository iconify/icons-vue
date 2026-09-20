<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/k/kinx7jb3n.css';
import '../../css/v/vxa4ihb0i.css';
import '../../css/d/dhfg-mgmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kinx7jb3n"/><path class="vxa4ihb0i"/><path clip-rule="evenodd" class="dhfg-mgmk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:document-sketch" /></template>
