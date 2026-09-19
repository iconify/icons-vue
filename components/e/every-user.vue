<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/q/qycvtdjfb.css';
import '../../css/q/qv3q5acwr.css';
import '../../css/k/kezi42cma.css';
import '../../css/o/ovtvrgkrb.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGveQDTbzg"><g class="aql7dnt-u"><circle class="qycvtdjfb"/><circle class="qv3q5acwr"/><circle class="kezi42cma"/><path class="ovtvrgkrb"/></g></mask></defs><path mask="url(#SVGveQDTbzg)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:every-user" /></template>
