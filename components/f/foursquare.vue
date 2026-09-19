<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/l/l9hcfvb2t.css';
import '../../css/u/uqe17tcka.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGnxiyGcFt"><g class="aql7dnt-u"><path class="l9hcfvb2t"/><path class="uqe17tcka"/></g></mask></defs><path mask="url(#SVGnxiyGcFt)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:foursquare" /></template>
