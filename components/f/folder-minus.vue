<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/h/h85pweb1l.css';
import '../../css/z/zqpa_ob9q.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGIIaB77rg"><g class="v3_i3wktz"><path class="h85pweb1l"/><path class="zqpa_ob9q"/></g></mask></defs><path mask="url(#SVGIIaB77rg)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:folder-minus" /></template>
