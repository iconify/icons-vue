<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/i/ifxv5jnsx.css';
import '../../css/m/m9g0m504h.css';
import '../../css/s/s91atubcm.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGAekilOfB"><g class="aql7dnt-u"><rect class="ifxv5jnsx"/><path class="m9g0m504h"/><path class="s91atubcm"/></g></mask></defs><path mask="url(#SVGAekilOfB)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:air-conditioning" /></template>
