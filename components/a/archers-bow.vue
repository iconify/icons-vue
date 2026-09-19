<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d79_wtv7f.css';
import '../../css/z/zu-gmcbwv.css';
import '../../css/v/v0m5xdb6q.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<mask id="ipSArchersBow0"><g class="ft5dv1b6b"><g clip-path="url(#ipSArchersBow1)" class="d79_wtv7f"><path class="zu-gmcbwv"/></g><defs><clipPath id="ipSArchersBow1"><path class="v0m5xdb6q"/></clipPath></defs></g></mask><path mask="url(#ipSArchersBow0)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:archers-bow" /></template>
