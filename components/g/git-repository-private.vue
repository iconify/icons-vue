<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/q409n5tsy.css';
import '../../css/m/mi4ud5ykd.css';
import '../../css/l/lz8pembln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="q409n5tsy"/><path class="mi4ud5ykd"/><path class="lz8pembln"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:git-repository-private" /></template>
