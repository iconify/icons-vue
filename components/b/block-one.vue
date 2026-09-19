<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3wltllsx.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGdXZvgbiJ"><path class="x3wltllsx"/></mask></defs><path mask="url(#SVGdXZvgbiJ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:block-one" /></template>
