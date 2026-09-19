<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/a/alx8q2bso.css';
import '../../css/a/as6-xr61g.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGWZkSzcLz"><g class="aql7dnt-u"><path class="alx8q2bso"/><path class="as6-xr61g"/></g></mask></defs><path mask="url(#SVGWZkSzcLz)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:holy-sword" /></template>
