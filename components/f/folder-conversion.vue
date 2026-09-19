<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/j/jexdvubgo.css';
import '../../css/b/b9ar51ayx.css';
import '../../css/p/p1ehdabkg.css';
import '../../css/f/f3gvbxbbm.css';
import '../../css/n/ns2om9uwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="jexdvubgo"/><path class="b9ar51ayx"/><path class="p1ehdabkg"/><path class="f3gvbxbbm"/><path class="ns2om9uwr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:folder-conversion" /></template>
