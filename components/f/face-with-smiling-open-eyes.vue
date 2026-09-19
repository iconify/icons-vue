<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/j/j-v2u4nhg.css';
import '../../css/i/i8k05e2ok.css';
import '../../css/a/a9pjw4axx.css';
import '../../css/q/q5n7lzb_t.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGnLJsUbdL"><g class="v3_i3wktz"><path class="j-v2u4nhg"/><path class="i8k05e2ok"/><circle class="a9pjw4axx"/><circle class="q5n7lzb_t"/></g></mask></defs><path mask="url(#SVGnLJsUbdL)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:face-with-smiling-open-eyes" /></template>
