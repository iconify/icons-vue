<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/l/l-ht24m0d.css';
import '../../css/r/rc8uiab2c.css';
import '../../css/b/b91i0on-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="wwvp95byt"><path class="l-ht24m0d"/><path class="rc8uiab2c"/><path clip-rule="evenodd" class="b91i0on-v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:damage-map" /></template>
