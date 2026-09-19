<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7g8vpbdo.css';
import '../../css/t/twovfhblf.css';
import '../../css/x/xdmpn7byu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="l7g8vpbdo"><path class="twovfhblf"/><path class="xdmpn7byu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:intermediate-mode" /></template>
