<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/n/nxl8u5bfk.css';
import '../../css/g/gnqtz4biq.css';
import '../../css/k/kmrt0suyf.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG5JP3obpr"><g class="wwvp95byt"><path class="nxl8u5bfk"/><path class="gnqtz4biq"/><path class="kmrt0suyf"/></g></mask></defs><path mask="url(#SVG5JP3obpr)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:invalid-files" /></template>
