<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_weg3b7j.css';
import '../../css/b/btnne-b7c.css';
import '../../css/j/jqwd5dbkd.css';
import '../../css/c/cgeb6tb7m.css';
import '../../css/x/xh7v49b4u.css';
import '../../css/r/r-rethkhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="j_weg3b7j"/><g class="btnne-b7c"><circle class="jqwd5dbkd"/><circle class="cgeb6tb7m"/><path class="xh7v49b4u"/><path class="r-rethkhw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:circled-human-figure" /></template>
