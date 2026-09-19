<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/c/clv75subd.css';
import '../../css/d/d_63unb4q.css';
import '../../css/q/qumoe9brk.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGiEVe8diH"><g class="s9cl3zbei"><path class="clv75subd"/><path class="d_63unb4q"/><path class="qumoe9brk"/></g></mask></defs><path mask="url(#SVGiEVe8diH)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:intercom" /></template>
