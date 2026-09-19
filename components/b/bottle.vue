<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/p/p928kbc7k.css';
import '../../css/n/n8izfmqik.css';
import '../../css/z/zfi3v6pvn.css';
import '../../css/z/z8d6w4btp.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGNlwrze2D"><g class="s9cl3zbei"><path class="p928kbc7k"/><path clip-rule="evenodd" class="n8izfmqik"/><path class="zfi3v6pvn"/><path class="z8d6w4btp"/></g></mask></defs><path mask="url(#SVGNlwrze2D)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:bottle" /></template>
