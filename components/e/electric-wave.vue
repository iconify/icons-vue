<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/h/h9qj9o6mz.css';
import '../../css/b/bhn8txt5s.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGvXj4Mc8N"><g class="aql7dnt-u"><rect class="h9qj9o6mz"/><path class="bhn8txt5s"/></g></mask></defs><path mask="url(#SVGvXj4Mc8N)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:electric-wave" /></template>
