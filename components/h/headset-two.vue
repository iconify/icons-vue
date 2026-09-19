<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/u/uc-2f9vbf.css';
import '../../css/k/k7sl3bboy.css';
import '../../css/r/rg5jo6gkv.css';
import '../../css/l/lxqcwwbex.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGTebUpqlO"><g class="aql7dnt-u"><path class="uc-2f9vbf"/><path class="k7sl3bboy"/><path class="rg5jo6gkv"/><path class="lxqcwwbex"/></g></mask></defs><path mask="url(#SVGTebUpqlO)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:headset-two" /></template>
