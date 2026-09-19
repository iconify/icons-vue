<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/v/v0dofs9fn.css';
import '../../css/h/hpluv7gvx.css';
import '../../css/w/wvkle8b0a.css';
import '../../css/i/i1qkqjmcg.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGGBoFQb9z"><g class="s9cl3zbei"><path class="v0dofs9fn"/><path class="hpluv7gvx"/><path class="wvkle8b0a"/><path class="i1qkqjmcg"/></g></mask></defs><path mask="url(#SVGGBoFQb9z)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:general-branch" /></template>
