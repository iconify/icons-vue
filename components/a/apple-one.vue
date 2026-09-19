<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/i/ijwf7s55v.css';
import '../../css/o/otjh3yf2h.css';
import '../../css/j/je3cg7brs.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGKtHq3p8r"><g class="s9cl3zbei"><path clip-rule="evenodd" class="ijwf7s55v"/><path class="otjh3yf2h"/><path class="je3cg7brs"/></g></mask></defs><path mask="url(#SVGKtHq3p8r)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:apple-one" /></template>
