<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/r/rt5_ebbas.css';
import '../../css/z/zqgbyob7l.css';
import '../../css/c/cfal8pb7y.css';
import '../../css/i/ii8d_pb8f.css';
import '../../css/b/bt1vyrbzr.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGlvwGebxY"><g class="ufeehvblu"><path class="rt5_ebbas"/><path class="zqgbyob7l"/><path class="cfal8pb7y"/><path class="ii8d_pb8f"/><path class="bt1vyrbzr"/></g></mask></defs><path mask="url(#SVGlvwGebxY)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:gift" /></template>
