<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/u/ug-3ocbdk.css';
import '../../css/q/qqb7s8hoo.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGzzRkYKZS"><g class="aql7dnt-u"><path class="ug-3ocbdk"/><path class="qqb7s8hoo"/></g></mask></defs><path mask="url(#SVGzzRkYKZS)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:loading-three" /></template>
