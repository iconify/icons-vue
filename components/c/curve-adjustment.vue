<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/f/fqzg-n1xw.css';
import '../../css/z/zz8y8qwjw.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGnogYlcWb"><g class="v3_i3wktz"><path class="fqzg-n1xw"/><path class="zz8y8qwjw"/></g></mask></defs><path mask="url(#SVGnogYlcWb)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:curve-adjustment" /></template>
