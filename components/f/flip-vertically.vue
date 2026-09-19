<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/v/v1s64tbtd.css';
import '../../css/t/t-44gy3jf.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGcbFV6bAw"><g class="v3_i3wktz"><path class="v1s64tbtd"/><path class="t-44gy3jf"/></g></mask></defs><path mask="url(#SVGcbFV6bAw)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:flip-vertically" /></template>
