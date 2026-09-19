<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/k/krf-rdb_i.css';
import '../../css/r/rgzmy_bcu.css';
import '../../css/v/v-gpjyjys.css';
import '../../css/p/pkewsubsz.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGP3x3Gdbc"><g class="aql7dnt-u"><path class="krf-rdb_i"/><path class="rgzmy_bcu"/><path class="v-gpjyjys"/><path class="pkewsubsz"/></g></mask></defs><path mask="url(#SVGP3x3Gdbc)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:goblet-full" /></template>
