<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/q/q62z-xbsl.css';
import '../../css/q/qd07iqr1b.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGZ9IljeSy"><g class="v3_i3wktz"><path class="q62z-xbsl"/><path class="qd07iqr1b"/></g></mask></defs><path mask="url(#SVGZ9IljeSy)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:connection-box" /></template>
