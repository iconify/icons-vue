<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/b/b8uij2b6n.css';
import '../../css/v/v6qg3zuvy.css';
import '../../css/g/gn6dmkbcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><rect class="b8uij2b6n"/><rect class="v6qg3zuvy"/><path class="gn6dmkbcd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:chip" /></template>
