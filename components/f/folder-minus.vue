<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/k/krz1plydf.css';
import '../../css/d/dv30fkbev.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGNtYAwbSA"><g class="ufeehvblu"><path class="krz1plydf"/><path class="dv30fkbev"/></g></mask></defs><path mask="url(#SVGNtYAwbSA)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:folder-minus" /></template>
