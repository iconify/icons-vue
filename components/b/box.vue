<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/u/uk6juhlzl.css';
import '../../css/b/b6sl7kbuk.css';
import '../../css/i/ib__xqbme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><rect class="uk6juhlzl"/><path class="b6sl7kbuk"/><path class="ib__xqbme"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:box" /></template>
