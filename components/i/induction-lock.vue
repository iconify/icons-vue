<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/z/zdr2iabse.css';
import '../../css/x/xsw5b7b3e.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGsQQEweKb"><g class="aql7dnt-u"><path class="zdr2iabse"/><path class="xsw5b7b3e"/></g></mask></defs><path mask="url(#SVGsQQEweKb)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:induction-lock" /></template>
