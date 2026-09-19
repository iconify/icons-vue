<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/b/bnqq59byx.css';
import '../../css/y/ypcu2o9-r.css';
import '../../css/v/vrkhalo1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bnqq59byx"/><path class="ypcu2o9-r"/><path class="vrkhalo1k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:evil" /></template>
