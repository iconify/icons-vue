<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uijzg9bmt.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGlxwUvcBQ"><path class="uijzg9bmt"/></mask></defs><path mask="url(#SVGlxwUvcBQ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:block-nine" /></template>
