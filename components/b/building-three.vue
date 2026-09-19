<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/p/p9msfmbxd.css';
import '../../css/i/itdqx4vmq.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGKLzWnbDx"><g class="aql7dnt-u"><path clip-rule="evenodd" class="p9msfmbxd"/><path class="itdqx4vmq"/></g></mask></defs><path mask="url(#SVGKLzWnbDx)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:building-three" /></template>
