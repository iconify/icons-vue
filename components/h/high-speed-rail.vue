<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nsue-fbyi.css';
import '../../css/a/a_-xyenlg.css';
import '../../css/j/j6yre1h3n.css';
import '../../css/k/kfssj3_4w.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGpppxA0ZV"><g class="ft5dv1b6b"><path class="nsue-fbyi"/><path class="a_-xyenlg"/><path class="j6yre1h3n"/><path class="kfssj3_4w"/></g></mask></defs><path mask="url(#SVGpppxA0ZV)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:high-speed-rail" /></template>
