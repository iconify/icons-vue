<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4wis2bvm.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGsu0PwdKx"><path class="x4wis2bvm"/></mask></defs><path mask="url(#SVGsu0PwdKx)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:filter" /></template>
