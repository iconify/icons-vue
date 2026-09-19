<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g-1apjy3m.css';
import '../../css/q/qfgi8xb7d.css';
import '../../css/d/df6umsjoq.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGrkwtXHMB"><g class="ft5dv1b6b"><path class="g-1apjy3m"/><path class="qfgi8xb7d"/><path class="df6umsjoq"/></g></mask></defs><path mask="url(#SVGrkwtXHMB)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:fireworks" /></template>
