<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n2b3f1bel.css';
import '../../css/b/bbxz0jq4i.css';
import '../../css/q/qtskb2sji.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGXHvbndxd"><g class="ft5dv1b6b"><path class="n2b3f1bel"/><path class="bbxz0jq4i"/><path clip-rule="evenodd" class="qtskb2sji"/></g></mask></defs><path mask="url(#SVGXHvbndxd)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:browser" /></template>
