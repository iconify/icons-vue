<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/z/z03iq3bby.css';
import '../../css/m/m9_4pob_d.css';
import '../../css/y/yqn8y9vgz.css';
import '../../css/g/grno8j8na.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="z03iq3bby"/><circle class="m9_4pob_d"/><path class="yqn8y9vgz"/><path class="grno8j8na"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:file-date-one" /></template>
