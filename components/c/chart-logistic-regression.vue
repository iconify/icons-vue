<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdoh_1bvl.css';
import '../../css/b/b0km5dbta.css';
import '../../css/u/u9yepu2ko.css';
import '../../css/y/yym454evr.css';
import '../../css/w/wp-7sd7au.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="mdoh_1bvl"/><circle class="b0km5dbta"/><circle class="u9yepu2ko"/><circle class="yym454evr"/><path class="wp-7sd7au"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-logistic-regression" /></template>
