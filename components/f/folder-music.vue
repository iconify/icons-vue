<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/j/jexdvubgo.css';
import '../../css/t/t_3zzecey.css';
import '../../css/p/pw4gvvwjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="jexdvubgo"/><path class="t_3zzecey"/><circle class="pw4gvvwjn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:folder-music" /></template>
