<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/f/fvc61obyz.css';
import '../../css/t/tkw6at4sn.css';
import '../../css/h/hnv_67brj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><rect class="fvc61obyz"/><path class="tkw6at4sn"/><path class="hnv_67brj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:laptop-computer" /></template>
