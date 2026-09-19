<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctj3b1blo.css';
import '../../css/a/a7ms1gb6t.css';
import '../../css/s/s77fccc8h.css';
import '../../css/w/wla87uw1c.css';
import '../../css/x/xad76ubit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ctj3b1blo"/><path class="a7ms1gb6t"/><g class="s77fccc8h"><circle class="wla87uw1c"/><path class="xad76ubit"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:contacts" /></template>
