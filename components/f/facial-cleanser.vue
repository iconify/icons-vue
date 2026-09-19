<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/q/q9_e0ab3k.css';
import '../../css/e/eiyu3qb0h.css';
import '../../css/e/ezkgjkbvi.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGTshhGczL"><g class="s9cl3zbei"><path class="q9_e0ab3k"/><path class="eiyu3qb0h"/><path class="ezkgjkbvi"/></g></mask></defs><path mask="url(#SVGTshhGczL)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:facial-cleanser" /></template>
