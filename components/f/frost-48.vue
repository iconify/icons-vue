<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhtqqrbcl.css';
import '../../css/g/gdgkf1jwj.css';
import '../../css/w/wu47-njnc.css';
import '../../css/w/w025bmewr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zhtqqrbcl"/><path class="gdgkf1jwj"/><path class="wu47-njnc"/><path class="w025bmewr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:frost-48" /></template>
