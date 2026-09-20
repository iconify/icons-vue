<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr52f_b5y.css';
import '../../css/g/g9rvrub_x.css';
import '../../css/h/h82gk3uiy.css';
import '../../css/n/n8uhd2kbj.css';
import '../../css/q/qoujeeb6i.css';
import '../../css/k/kqhxncb0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="g9rvrub_x"/><path class="h82gk3uiy"/><ellipse class="n8uhd2kbj"/><ellipse class="qoujeeb6i"/><path class="kqhxncb0k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-smile-line-duotone" /></template>
