<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/t/tl8r9hb7v.css';
import '../../css/m/mqljzjkxs.css';
import '../../css/o/ok_dmqrra.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGkGn1UcxB"><g class="v3_i3wktz"><path clip-rule="evenodd" class="tl8r9hb7v"/><path class="mqljzjkxs"/><path class="ok_dmqrra"/></g></mask></defs><path mask="url(#SVGkGn1UcxB)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:cooking-pot" /></template>
