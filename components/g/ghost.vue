<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/a/a8rml3bpr.css';
import '../../css/a/am3i6jbjw.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGY0EtEeTz"><g class="ufeehvblu"><path class="a8rml3bpr"/><path class="am3i6jbjw"/></g></mask></defs><path mask="url(#SVGY0EtEeTz)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:ghost" /></template>
