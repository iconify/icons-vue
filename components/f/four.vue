<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k75we7n6d.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGrYVhzblO"><path class="k75we7n6d"/></mask></defs><path mask="url(#SVGrYVhzblO)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:four" /></template>
