<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzhos931o.css';
import '../../css/w/wjcjnmb0r.css';
import '../../css/d/doj9dq_jg.css';
import '../../css/s/susxgukgt.css';
import '../../css/c/cz7q87nyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="kzhos931o"/><path class="wjcjnmb0r"/><g class="doj9dq_jg"><path class="susxgukgt"/><path class="cz7q87nyz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:cloud-with-lightning" /></template>
