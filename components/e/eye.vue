<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2w8m1bts.css';
import '../../css/s/st6zf__cy.css';
import '../../css/f/fpuu3bcbf.css';
import '../../css/c/czclt8bgq.css';
import '../../css/y/yoa9wypyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c2w8m1bts"/><path class="st6zf__cy"/><path class="fpuu3bcbf"/><path class="czclt8bgq"/><path class="yoa9wypyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:eye" /></template>
