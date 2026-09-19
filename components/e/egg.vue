<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/d/dvcapvbcu.css';
import '../../css/n/n3y4iwy_t.css';
import '../../css/s/szdnrl1jv.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGEhaW4dLm"><g class="s9cl3zbei"><circle class="dvcapvbcu"/><path class="n3y4iwy_t"/><path class="szdnrl1jv"/></g></mask></defs><path mask="url(#SVGEhaW4dLm)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:egg" /></template>
