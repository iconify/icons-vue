<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/m/mm938ojjy.css';
import '../../css/u/u6s_gabnn.css';
import '../../css/g/ghea5cbsp.css';
import '../../css/j/j2m8g8spq.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGA1Z3kdCa"><g class="aql7dnt-u"><path class="mm938ojjy"/><path class="u6s_gabnn"/><circle class="ghea5cbsp"/><path class="j2m8g8spq"/></g></mask></defs><path mask="url(#SVGA1Z3kdCa)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:folder" /></template>
