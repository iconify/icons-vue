<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/c/ct1r7w1hv.css';
import '../../css/l/lmhlr-bsl.css';
import '../../css/x/xu7x7kbnb.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG6S9q1S5Z"><g class="v3_i3wktz"><path class="ct1r7w1hv"/><path class="lmhlr-bsl"/><path class="xu7x7kbnb"/></g></mask></defs><path mask="url(#SVG6S9q1S5Z)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:inbox-in" /></template>
