<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/f/fghv1qb6b.css';
import '../../css/v/vtcx4tbpp.css';
import '../../css/i/iv925zzmn.css';
import '../../css/j/jcrlfrbgh.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGgtKiTdXu"><g class="aql7dnt-u"><path class="fghv1qb6b"/><path class="vtcx4tbpp"/><path clip-rule="evenodd" class="iv925zzmn"/><path class="jcrlfrbgh"/></g></mask></defs><path mask="url(#SVGgtKiTdXu)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:bedside-two" /></template>
