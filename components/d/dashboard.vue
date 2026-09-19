<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3lph30dl.css';
import '../../css/b/beip37bcn.css';
import '../../css/w/w4fezhbzj.css';
import '../../css/q/qyky4f0vl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="beip37bcn"/><path class="w4fezhbzj"/><path class="qyky4f0vl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:dashboard" /></template>
