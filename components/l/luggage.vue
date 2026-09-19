<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/di7205bgb.css';
import '../../css/j/jd-n5bc_b.css';
import '../../css/g/gt65h22tq.css';
import '../../css/h/h0s5wccqo.css';
import '../../css/t/therzxb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="di7205bgb"/><path clip-rule="evenodd" class="jd-n5bc_b"/><path class="gt65h22tq"/><path clip-rule="evenodd" class="h0s5wccqo"/><path class="therzxb5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:luggage" /></template>
