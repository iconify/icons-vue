<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/c/c86dgmbjh.css';
import '../../css/g/gyui38byj.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGtKrLJTTk"><g class="v3_i3wktz"><path class="c86dgmbjh"/><path class="gyui38byj"/></g></mask></defs><path mask="url(#SVGtKrLJTTk)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:align-bottom" /></template>
