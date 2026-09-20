<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie3fup9fg.css';
import '../../css/l/lsattvb1c.css';
import '../../css/x/x6mcnkwhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ie3fup9fg"/><path class="lsattvb1c"/><path class="x6mcnkwhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:design-hilight" /></template>
