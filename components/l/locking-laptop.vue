<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/e/e8jxhdczm.css';
import '../../css/s/skzye-b9q.css';
import '../../css/p/pwvf6kbgi.css';
import '../../css/j/jh_hxtbax.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG3KzmBdke"><g class="v3_i3wktz"><path class="e8jxhdczm"/><path class="skzye-b9q"/><rect class="pwvf6kbgi"/><path class="jh_hxtbax"/></g></mask></defs><path mask="url(#SVG3KzmBdke)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:locking-laptop" /></template>
