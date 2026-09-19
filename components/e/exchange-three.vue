<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/u/ulkx0nbdh.css';
import '../../css/t/tdrgxhknx.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGbSBuC8ZU"><g class="v3_i3wktz"><path class="ulkx0nbdh"/><path class="tdrgxhknx"/></g></mask></defs><path mask="url(#SVGbSBuC8ZU)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:exchange-three" /></template>
