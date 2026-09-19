<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eafecig_w.css';
import '../../css/u/ufikoxbls.css';
import '../../css/h/h9cimjbxp.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="clr-i-outline clr-i-outline-path-1 eafecig_w"/><circle class="clr-i-outline clr-i-outline-path-2 ufikoxbls"/><circle class="clr-i-outline clr-i-outline-path-3 h9cimjbxp"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:ellipsis-vertical-line" /></template>
