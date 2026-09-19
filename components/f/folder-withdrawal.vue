<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/b/bcqa_q4nr.css';
import '../../css/u/ursccdz5i.css';
import '../../css/q/q3_2n5bmx.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGdNghrdfj"><g class="ufeehvblu"><path class="bcqa_q4nr"/><path class="ursccdz5i"/><path class="q3_2n5bmx"/></g></mask></defs><path mask="url(#SVGdNghrdfj)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:folder-withdrawal" /></template>
