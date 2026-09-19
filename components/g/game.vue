<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/p/pr5-tsckb.css';
import '../../css/t/tz8fk5bif.css';
import '../../css/f/ffm55kuxg.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGGMJ8veDU"><g class="v3_i3wktz"><path class="pr5-tsckb"/><path class="tz8fk5bif"/><path class="ffm55kuxg"/></g></mask></defs><path mask="url(#SVGGMJ8veDU)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:game" /></template>
