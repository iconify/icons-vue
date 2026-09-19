<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l9j-zbc3e.css';
import '../../css/a/apd31-bcn.css';
import '../../css/t/te8y23ggl.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGsBC8zbiD"><g class="ft5dv1b6b"><path clip-rule="evenodd" class="l9j-zbc3e"/><path class="apd31-bcn"/><path class="te8y23ggl"/></g></mask></defs><path mask="url(#SVGsBC8zbiD)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:car" /></template>
