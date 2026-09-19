<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9sroks9g.css';
import '../../css/s/s53vmbcgz.css';
import '../../css/r/rlosknbna.css';
import '../../css/k/kmezwrwcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k9sroks9g"/><g class="s53vmbcgz"><path class="rlosknbna"/><path class="kmezwrwcb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:luau-client" /></template>
