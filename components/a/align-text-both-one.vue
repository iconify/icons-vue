<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/x/xhdah4bbl.css';
import '../../css/b/beorgl7xp.css';
import '../../css/i/iu_7h2b0u.css';
import '../../css/j/jtgskbcrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><rect class="xhdah4bbl"/><path class="beorgl7xp"/><path class="iu_7h2b0u"/><path class="jtgskbcrm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:align-text-both-one" /></template>
