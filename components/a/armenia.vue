<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufvrkebxw.css';
import '../../css/o/owp3yfbrj.css';
import '../../css/v/v4iawlr0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="ufvrkebxw"/><path class="owp3yfbrj"/><path class="v4iawlr0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:armenia" /></template>
