<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/i/ikbleibbz.css';
import '../../css/u/ue1cjpbqo.css';
import '../../css/l/lop3_mics.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGMw63ncxY"><g class="aql7dnt-u"><circle class="ikbleibbz"/><path class="ue1cjpbqo"/><path class="lop3_mics"/></g></mask></defs><path mask="url(#SVGMw63ncxY)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:edit-name" /></template>
