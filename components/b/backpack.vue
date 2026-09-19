<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/r/rc4qhib2b.css';
import '../../css/v/vle878-ex.css';
import '../../css/h/hej9tpb-u.css';
import '../../css/s/se7dw-m9u.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG1C6FqcGC"><g class="wwvp95byt"><path class="rc4qhib2b"/><path class="vle878-ex"/><path class="hej9tpb-u"/><path class="se7dw-m9u"/></g></mask></defs><path mask="url(#SVG1C6FqcGC)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:backpack" /></template>
