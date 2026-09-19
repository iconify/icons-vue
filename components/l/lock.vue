<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/a/a0v65gtra.css';
import '../../css/q/qebjus5ad.css';
import '../../css/e/ejxs69auf.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGtDIhpJdd"><g class="ufeehvblu"><rect class="a0v65gtra"/><path class="qebjus5ad"/><path class="ejxs69auf"/></g></mask></defs><path mask="url(#SVGtDIhpJdd)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:lock" /></template>
