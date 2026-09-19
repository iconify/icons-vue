<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/q/qt1es7b7z.css';
import '../../css/l/l_tp72bqp.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGEr0T1crA"><g class="aql7dnt-u"><path class="qt1es7b7z"/><path class="l_tp72bqp"/></g></mask></defs><path mask="url(#SVGEr0T1crA)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:landing" /></template>
