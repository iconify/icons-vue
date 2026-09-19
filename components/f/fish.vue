<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/s--u84b9a.css';
import '../../css/e/ej7hsirhs.css';
import '../../css/i/iur5ai2ln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="s--u84b9a"/><path class="ej7hsirhs"/><path class="iur5ai2ln"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:fish" /></template>
