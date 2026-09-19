<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/e/ebl78obby.css';
import '../../css/u/u0zcdxb8y.css';
import '../../css/o/odgjuccph.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGjOy5gcWI"><g class="ufeehvblu"><path class="ebl78obby"/><path class="u0zcdxb8y"/><path class="odgjuccph"/></g></mask></defs><path mask="url(#SVGjOy5gcWI)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:consume" /></template>
