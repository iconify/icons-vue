<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/z/zdhb83szs.css';
import '../../css/r/rpsd5vp5o.css';
import '../../css/r/rsvuxndka.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGKpq6fc5u"><g class="ufeehvblu"><path class="zdhb83szs"/><path class="rpsd5vp5o"/><path class="rsvuxndka"/></g></mask></defs><path mask="url(#SVGKpq6fc5u)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:local" /></template>
