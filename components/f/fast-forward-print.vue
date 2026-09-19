<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nctb2ac4r.css';
import '../../css/m/m-8maggzp.css';
import '../../css/h/hi4zbii8j.css';
import '../../css/h/hco4yqb6k.css';
import '../../css/a/a25kz8bfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><g class="nctb2ac4r"><path class="m-8maggzp"/><path class="hi4zbii8j"/></g><path clip-rule="evenodd" class="hco4yqb6k"/><path clip-rule="evenodd" class="a25kz8bfm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:fast-forward-print" /></template>
