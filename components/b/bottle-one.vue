<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/s/syw2plbjf.css';
import '../../css/r/r7e936b3o.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG24aNScsn"><g class="aql7dnt-u"><path class="syw2plbjf"/><path class="r7e936b3o"/></g></mask></defs><path mask="url(#SVG24aNScsn)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:bottle-one" /></template>
