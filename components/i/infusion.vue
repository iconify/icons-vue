<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/a/a4fw-bcwn.css';
import '../../css/b/buzi5ibmp.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGP6gv1bnK"><g class="v3_i3wktz"><path class="a4fw-bcwn"/><path class="buzi5ibmp"/></g></mask></defs><path mask="url(#SVGP6gv1bnK)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:infusion" /></template>
