<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayhad1bui.css';
import '../../css/t/tis514fms.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="ayhad1bui clr-i-outline clr-i-outline-path-1"/><path class="clr-i-outline clr-i-outline-path-2 tis514fms"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:install-line" /></template>
