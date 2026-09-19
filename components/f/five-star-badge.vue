<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv9y21t5h.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGfoAOLxWE"><path class="kv9y21t5h"/></mask></defs><path mask="url(#SVGfoAOLxWE)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:five-star-badge" /></template>
