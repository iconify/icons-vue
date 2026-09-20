<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmpuuq6uh.css';
import '../../css/t/tq81vbcsk.css';
import '../../css/m/mhz4m5u4t.css';
import '../../css/w/wtlifrzdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gmpuuq6uh"/><path class="tq81vbcsk"/><path class="mhz4m5u4t"/><path class="wtlifrzdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:apps-script" /></template>
