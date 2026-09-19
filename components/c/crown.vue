<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/v/vrj7zob5e.css';
import '../../css/g/ghrjw3d7b.css';
import '../../css/x/xdn6abclq.css';
import '../../css/z/z3t4bn4rn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="vrj7zob5e"/><circle class="ghrjw3d7b"/><circle class="xdn6abclq"/><circle class="z3t4bn4rn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:crown" /></template>
