<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3lph30dl.css';
import '../../css/s/sh2szbc6h.css';
import '../../css/k/kzochbc7e.css';
import '../../css/z/zhr8h_jpw.css';
import '../../css/g/goslebblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="sh2szbc6h"/><path class="kzochbc7e"/><path class="zhr8h_jpw"/><path class="goslebblv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:api-app" /></template>
