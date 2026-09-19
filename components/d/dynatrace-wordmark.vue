<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5_811bpr.css';
import '../../css/f/flmm__5bu.css';
import '../../css/a/a47t9qbyk.css';
import '../../css/x/xpodimlxf.css';
import '../../css/e/ejjzxeb3n.css';
import '../../css/m/mi9nofbit.css';
import '../../css/e/egchxsbhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="b5_811bpr"/><path class="flmm__5bu"/><path class="a47t9qbyk"/><path class="xpodimlxf"/><path class="ejjzxeb3n"/><path class="mi9nofbit"/><path class="egchxsbhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:dynatrace-wordmark" /></template>
