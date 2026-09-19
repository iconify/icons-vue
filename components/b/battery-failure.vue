<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jain414ui.css';
import '../../css/r/r_0d81uyp.css';
import '../../css/n/nol_dj69e.css';
import '../../css/b/bon6j1b7a.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG6yIQDeGj"><g class="ft5dv1b6b"><rect transform="rotate(-90 14 44)" class="jain414ui"/><path class="r_0d81uyp"/><path class="nol_dj69e"/><path class="bon6j1b7a"/></g></mask></defs><path mask="url(#SVG6yIQDeGj)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:battery-failure" /></template>
