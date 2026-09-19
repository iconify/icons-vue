<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bywdou5mv.css';
import '../../css/g/gqo6vsblf.css';
import '../../css/n/n4bbqnbhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="bywdou5mv"/><path class="gqo6vsblf"/><path class="n4bbqnbhj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:hammer-and-pick" /></template>
