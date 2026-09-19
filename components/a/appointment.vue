<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/z/z4bieue7t.css';
import '../../css/n/nb4q60bwm.css';
import '../../css/d/dtbcdossj.css';
import '../../css/m/mea8r4fbu.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGBHGQ4qJY"><g class="s9cl3zbei"><circle class="z4bieue7t"/><path class="nb4q60bwm"/><circle class="dtbcdossj"/><path class="mea8r4fbu"/></g></mask></defs><path mask="url(#SVGBHGQ4qJY)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:appointment" /></template>
