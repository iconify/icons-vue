<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb3dnfb0c.css';
import '../../css/g/gsllvxbkr.css';
import '../../css/k/k09zifbmd.css';
import '../../css/x/x7axkclvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cb3dnfb0c"/><g class="gsllvxbkr"><path class="k09zifbmd"/><path class="x7axkclvw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:bearish" /></template>
