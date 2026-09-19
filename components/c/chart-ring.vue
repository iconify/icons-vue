<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/b/bzk2ng9yc.css';
import '../../css/i/iz7o08dmv.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGZYLLyNIJ"><g class="v3_i3wktz"><path class="bzk2ng9yc"/><path class="iz7o08dmv"/></g></mask></defs><path mask="url(#SVGZYLLyNIJ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:chart-ring" /></template>
