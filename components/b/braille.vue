<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8h5q9-0j.css';
import '../../css/f/fzegkjtdu.css';
import '../../css/j/jk7w2ccjf.css';
import '../../css/e/ejjj98u7g.css';
import '../../css/c/ci4mzpb8t.css';
import '../../css/f/f3oymzbtg.css';
import '../../css/t/trckxm5te.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="f8h5q9-0j"/><circle class="fzegkjtdu"/><circle class="jk7w2ccjf"/><circle class="ejjj98u7g"/><circle class="ci4mzpb8t"/><circle class="f3oymzbtg"/><circle class="trckxm5te"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:braille" /></template>
