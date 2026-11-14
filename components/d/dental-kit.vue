<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lod1jac9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dental-kit" /></template>
<style>
.lod1jac9f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m13.945 3.252l.707-.707q1.59-1.591 3.181 0q.288.287.45.626q.054-.038.113-.066t.124-.046q.063-.018.129-.024t.131 0q.066.005.13.022t.124.045t.114.065t.1.085q.106.105.163.243t.057.287t-.057.287t-.163.243l-1.415 1.416l-.707.706v.001L13.811 9.75H18q1.76 0 3.005 1.245T22.25 14v3.5q0 1.76-1.245 3.005T18 21.75H6q-1.76 0-3.005-1.245T1.75 17.5V14q0-1.76 1.245-3.005q.356-.357.755-.611V8q0-1.75 1.75-1.75h4q1.75 0 1.75 1.75v1.75h.439l2.839-2.839q-.291-.185-.583-.477q-.66-.659-.66-1.591t.66-1.591M6 9.75h3.75V8q0-.25-.25-.25h-4q-.25 0-.25.25v1.81q.363-.06.75-.06");
}

</style>
