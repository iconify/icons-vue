<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2cxhrb1t.css';
import '../../css/z/zjuzcpbhe.css';
import '../../css/a/ayo620-7m.css';
import '../../css/h/h6gdwbeok.css';
import '../../css/b/br579xj1y.css';
import '../../css/r/r83crp8zv.css';
import '../../css/o/omnphvblp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="q2cxhrb1t"/><path class="zjuzcpbhe"/><path class="ayo620-7m"/><path class="h6gdwbeok"/><path class="br579xj1y"/><path class="r83crp8zv"/><path class="omnphvblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:drupal" /></template>
