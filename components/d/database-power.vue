<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/d/dtwjw7ica.css';
import '../../css/l/lcee_744z.css';
import '../../css/m/mb-fyjb0d.css';
import '../../css/e/em51ylqbe.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGlSYx9dwI"><g class="aql7dnt-u"><path class="dtwjw7ica"/><path class="lcee_744z"/><path class="mb-fyjb0d"/><path class="em51ylqbe"/></g></mask></defs><path mask="url(#SVGlSYx9dwI)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:database-power" /></template>
