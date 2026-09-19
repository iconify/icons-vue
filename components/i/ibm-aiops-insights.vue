<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq-zceb_w.css';
import '../../css/r/rhd8cdczy.css';
import '../../css/w/wuev9cbck.css';
import '../../css/g/gjeb820rg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lq-zceb_w"/><path class="rhd8cdczy"/><path class="wuev9cbck"/><circle class="gjeb820rg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-aiops-insights" /></template>
