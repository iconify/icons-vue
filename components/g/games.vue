<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc8hhiglu.css';
import '../../css/o/ot71gxx5a.css';
import '../../css/i/i9-6g599y.css';
import '../../css/m/mrjw428aa.css';
import '../../css/m/m9st3rkyl.css';
import '../../css/v/vfjy9g0uf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<circle class="sc8hhiglu"/><path class="ot71gxx5a"/><circle class="i9-6g599y"/><circle class="mrjw428aa"/><path class="m9st3rkyl"/><circle class="vfjy9g0uf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-ui:games" /></template>
