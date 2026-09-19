<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/m/mfdv7o-jc.css';
import '../../css/m/m-__3gzel.css';
import '../../css/i/i58gqscgg.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGduo1ntkh"><g class="ufeehvblu"><rect class="mfdv7o-jc"/><path class="m-__3gzel"/><path class="i58gqscgg"/></g></mask></defs><path mask="url(#SVGduo1ntkh)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:box" /></template>
