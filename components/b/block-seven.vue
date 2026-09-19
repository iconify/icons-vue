<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x853vnbqo.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGa6UUhcmp"><path class="x853vnbqo"/></mask></defs><path mask="url(#SVGa6UUhcmp)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:block-seven" /></template>
