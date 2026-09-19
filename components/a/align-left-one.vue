<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv130ab-t.css';
import '../../css/z/zm1am8zwq.css';
import '../../css/g/ghilmzbaa.css';
import '../../css/a/a_66_cbsw.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGJQBRUoTK"><g class="hv130ab-t"><path class="zm1am8zwq"/><path class="ghilmzbaa"/><path class="a_66_cbsw"/></g></mask></defs><path mask="url(#SVGJQBRUoTK)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:align-left-one" /></template>
