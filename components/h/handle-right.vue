<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/v/vcum2uxal.css';
import '../../css/o/odgo2qjxq.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGe5DFsbhx"><g class="ufeehvblu"><rect class="vcum2uxal"/><path class="odgo2qjxq"/></g></mask></defs><path mask="url(#SVGe5DFsbhx)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:handle-right" /></template>
