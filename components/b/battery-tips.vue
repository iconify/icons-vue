<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jain414ui.css';
import '../../css/r/r_0d81uyp.css';
import '../../css/y/yxum4bbmw.css';
import '../../css/k/k1uq304yb.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGoqDEZcaz"><g class="ft5dv1b6b"><rect transform="rotate(-90 14 44)" class="jain414ui"/><path class="r_0d81uyp"/><path class="yxum4bbmw"/><circle transform="matrix(0 -1 -1 0 24 34)" class="k1uq304yb"/></g></mask></defs><path mask="url(#SVGoqDEZcaz)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:battery-tips" /></template>
