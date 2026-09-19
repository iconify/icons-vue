<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2-13jbdu.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGGJR8obeK"><path class="o2-13jbdu"/></mask></defs><path mask="url(#SVGGJR8obeK)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:five" /></template>
