<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-5av7bmy.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGt9zVddCE"><path clip-rule="evenodd" class="j-5av7bmy"/></mask></defs><path mask="url(#SVGt9zVddCE)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:back" /></template>
