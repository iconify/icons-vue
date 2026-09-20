<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmi7xr5ec.css';
import '../../css/r/r63xavbvd.css';
import '../../css/b/bpn6pm9pz.css';
import '../../css/h/h1ql855rm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mmi7xr5ec"/><path class="r63xavbvd"/><path class="bpn6pm9pz"/><path class="h1ql855rm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lidbrainz-dark" /></template>
