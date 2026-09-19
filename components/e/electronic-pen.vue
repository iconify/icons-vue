<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z74vh5rme.css';
import '../../css/m/mtra8c3lj.css';
import '../../css/h/hwsk9gqbj.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGilHgNmUP"><g class="ft5dv1b6b"><rect transform="rotate(45 35.193 5.322)" class="z74vh5rme"/><path class="mtra8c3lj"/><rect transform="rotate(30 33.268 12.34)" class="hwsk9gqbj"/></g></mask></defs><path mask="url(#SVGilHgNmUP)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:electronic-pen" /></template>
