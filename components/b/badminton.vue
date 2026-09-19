<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqznn1ydc.css';
import '../../css/a/a4v76gi7m.css';
import '../../css/w/wt1fcu4ke.css';
import '../../css/k/kmj7kph2b.css';
import '../../css/z/zb_4k5z-h.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG4M0msdHi"><g class="wqznn1ydc"><path class="a4v76gi7m"/><path class="wt1fcu4ke"/><path class="kmj7kph2b"/><path class="zb_4k5z-h"/></g></mask></defs><path mask="url(#SVG4M0msdHi)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:badminton" /></template>
