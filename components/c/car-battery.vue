<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/q/qblb5vb-h.css';
import '../../css/k/ksfo9sa3u.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGhgbF1H4Z"><g class="aql7dnt-u"><path class="qblb5vb-h"/><path class="ksfo9sa3u"/></g></mask></defs><path mask="url(#SVGhgbF1H4Z)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:car-battery" /></template>
