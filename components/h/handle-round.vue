<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/m/mzszod_2j.css';
import '../../css/g/gpapefbnn.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGhAWSuKir"><g class="wwvp95byt"><circle class="mzszod_2j"/><circle class="gpapefbnn"/></g></mask></defs><path mask="url(#SVGhAWSuKir)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:handle-round" /></template>
