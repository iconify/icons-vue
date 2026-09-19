<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/i/i_rbvcu_z.css';
import '../../css/s/saeqq1b-z.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG6GoIwbMs"><g class="ufeehvblu"><path class="i_rbvcu_z"/><path class="saeqq1b-z"/></g></mask></defs><path mask="url(#SVG6GoIwbMs)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:file-excel" /></template>
