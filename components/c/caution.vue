<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/e/e6xwq7bwr.css';
import '../../css/s/sa6e5v3it.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG5u6ebeaz"><g class="s9cl3zbei"><path clip-rule="evenodd" class="e6xwq7bwr"/><path class="sa6e5v3it"/></g></mask></defs><path mask="url(#SVG5u6ebeaz)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:caution" /></template>
