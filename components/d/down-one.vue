<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec97uj83u.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGwTKYc5fj"><path class="ec97uj83u"/></mask></defs><path mask="url(#SVGwTKYc5fj)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:down-one" /></template>
