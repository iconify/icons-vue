<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/o/ode45e42f.css';
import '../../css/j/j4e641bye.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGUYR4IUYW"><g class="v3_i3wktz"><path class="ode45e42f"/><path class="j4e641bye"/></g></mask></defs><path mask="url(#SVGUYR4IUYW)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:chart-graph" /></template>
