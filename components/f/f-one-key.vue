<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/h/h9qj9o6mz.css';
import '../../css/u/u5_ihmctb.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG3QysAbSN"><g class="aql7dnt-u"><rect class="h9qj9o6mz"/><path class="u5_ihmctb"/></g></mask></defs><path mask="url(#SVG3QysAbSN)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:f-one-key" /></template>
