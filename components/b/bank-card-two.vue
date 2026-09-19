<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/t/tw_yk0f4z.css';
import '../../css/v/vb00zyb1i.css';
import '../../css/i/icd8z0b3b.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGEorTQdnf"><g class="ufeehvblu"><path class="tw_yk0f4z"/><path class="vb00zyb1i"/><path class="icd8z0b3b"/></g></mask></defs><path mask="url(#SVGEorTQdnf)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:bank-card-two" /></template>
