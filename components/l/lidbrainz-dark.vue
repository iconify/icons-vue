<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmi7xr5ec.css';
import '../../css/r/re6u8gbgx.css';
import '../../css/b/bpn6pm9pz.css';
import '../../css/u/uacs7ebvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mmi7xr5ec"/><path class="re6u8gbgx"/><path class="bpn6pm9pz"/><path class="uacs7ebvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lidbrainz-dark" /></template>
