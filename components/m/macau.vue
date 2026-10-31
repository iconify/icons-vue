<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7ezobcke.css';
import '../../css/c/chm7fdc5b.css';
import '../../css/v/v66gpt9yj.css';
import '../../css/l/lmbelcc2s.css';
import '../../css/k/k8ofb3baa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="c7ezobcke"/><path class="chm7fdc5b"/><path class="v66gpt9yj"/><path class="lmbelcc2s"/><path class="k8ofb3baa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:macau" /></template>
