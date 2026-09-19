<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/k/km8h23fgj.css';
import '../../css/x/x_b3i0b1s.css';
import '../../css/q/qq3uxvb1o.css';
import '../../css/b/bg4k9rbrb.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG7TQpMdjP"><g class="s9cl3zbei"><path class="km8h23fgj"/><circle class="x_b3i0b1s"/><path class="qq3uxvb1o"/><path class="bg4k9rbrb"/></g></mask></defs><path mask="url(#SVG7TQpMdjP)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:file-date-one" /></template>
