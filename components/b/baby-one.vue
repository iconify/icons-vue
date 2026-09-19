<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv130ab-t.css';
import '../../css/e/enqwhf6kv.css';
import '../../css/g/glxmc61cx.css';
import '../../css/j/jdgziibth.css';
import '../../css/s/sghdsebar.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGgfQvmeFq"><g class="hv130ab-t"><circle class="enqwhf6kv"/><path class="glxmc61cx"/><path class="jdgziibth"/><path class="sghdsebar"/></g></mask></defs><path mask="url(#SVGgfQvmeFq)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:baby-one" /></template>
