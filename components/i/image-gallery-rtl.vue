<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpfg3lbzb.css';
import '../../css/g/g26fkqble.css';
import '../../css/p/px4i0s1qf.css';
import '../../css/l/lk2oa9bac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rpfg3lbzb"/><path class="g26fkqble"/><path class="px4i0s1qf"/><circle class="lk2oa9bac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:image-gallery-rtl" /></template>
