<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/d/drz-q8q9v.css';
import '../../css/p/p-rbzybho.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGtcYcYcZi"><g class="ufeehvblu"><path class="drz-q8q9v"/><path class="p-rbzybho"/></g></mask></defs><path mask="url(#SVGtcYcYcZi)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:infusion" /></template>
