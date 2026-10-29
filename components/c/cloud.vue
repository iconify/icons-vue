<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gclruccxz.css';
import '../../css/c/cjn1qbxvz.css';
import '../../css/m/mk10qibjs.css';
import '../../css/l/lc5e75zoy.css';
import '../../css/w/w2hy3bjtm.css';
import '../../css/h/h3mbwmriq.css';
import '../../css/x/x4zqg1bmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gclruccxz wm-shadow"/><path class="cjn1qbxvz"/><path class="mk10qibjs"/><path class="lc5e75zoy"/><path class="w2hy3bjtm"/><path class="h3mbwmriq wm-shine"/><path class="x4zqg1bmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-plush:cloud" /></template>
