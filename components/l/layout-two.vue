<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/h/h9qj9o6mz.css';
import '../../css/w/w-3mi7j8w.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGWFiNMeUh"><g class="v3_i3wktz"><rect class="h9qj9o6mz"/><path class="w-3mi7j8w"/></g></mask></defs><path mask="url(#SVGWFiNMeUh)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:layout-two" /></template>
