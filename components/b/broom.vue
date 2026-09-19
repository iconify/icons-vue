<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l7zjx1lhs.css';
import '../../css/h/hjnra_0-x.css';
import '../../css/b/b5_ngdv9b.css';
import '../../css/t/t4b5bjr0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="l7zjx1lhs"/><path class="hjnra_0-x"/><path class="b5_ngdv9b"/><path class="t4b5bjr0k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:broom" /></template>
