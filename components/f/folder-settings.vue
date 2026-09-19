<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/m/msv6_bc6s.css';
import '../../css/v/vfmzgoj_w.css';
import '../../css/t/tn3zsp5hd.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGFl2AIcQH"><g class="s9cl3zbei"><path class="msv6_bc6s"/><circle class="vfmzgoj_w"/><path class="tn3zsp5hd"/></g></mask></defs><path mask="url(#SVGFl2AIcQH)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:folder-settings" /></template>
