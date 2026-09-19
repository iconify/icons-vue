<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/k/k7vqv1bha.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGEQR2fbbp"><g class="ufeehvblu"><path class="oo_vs07_g"/><path class="k7vqv1bha"/></g></mask></defs><path mask="url(#SVGEQR2fbbp)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:electrocardiogram" /></template>
