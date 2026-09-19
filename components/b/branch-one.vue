<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/b/b8cd-f9hp.css';
import '../../css/k/kzptuhikc.css';
import '../../css/d/d8x3xzbpj.css';
import '../../css/y/yr5k3xbui.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGSHsbMe7A"><g class="aql7dnt-u"><path class="b8cd-f9hp"/><path class="kzptuhikc"/><path class="d8x3xzbpj"/><path class="yr5k3xbui"/></g></mask></defs><path mask="url(#SVGSHsbMe7A)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:branch-one" /></template>
