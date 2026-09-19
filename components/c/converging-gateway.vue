<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/e/ez330t4ze.css';
import '../../css/k/kdkps0bit.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGdn7wKcOR"><g class="s9cl3zbei"><path class="ez330t4ze"/><path class="kdkps0bit"/></g></mask></defs><path mask="url(#SVGdn7wKcOR)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:converging-gateway" /></template>
