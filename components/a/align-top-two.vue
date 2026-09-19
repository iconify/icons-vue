<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umcihdb7e.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGJKBlpclM"><path class="umcihdb7e"/></mask></defs><path mask="url(#SVGJKBlpclM)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:align-top-two" /></template>
