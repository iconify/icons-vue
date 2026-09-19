<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/m/m3rbq0wjz.css';
import '../../css/o/ozv-chpao.css';
import '../../css/q/qni72ecbz.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG2ykNtbBm"><g class="aql7dnt-u"><path class="m3rbq0wjz"/><path class="ozv-chpao"/><path class="qni72ecbz"/></g></mask></defs><path mask="url(#SVG2ykNtbBm)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:file-lock-one" /></template>
