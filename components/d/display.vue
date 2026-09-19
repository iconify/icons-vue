<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/j/j6j72ac8t.css';
import '../../css/f/f28irgb8p.css';
import '../../css/m/mqge99bdl.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGBTwGNeNh"><g class="ufeehvblu"><rect class="j6j72ac8t"/><path class="f28irgb8p"/><path class="mqge99bdl"/></g></mask></defs><path mask="url(#SVGBTwGNeNh)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:display" /></template>
