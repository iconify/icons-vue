<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkah-u8kr.css';
import '../../css/h/h536d422m.css';
import '../../css/t/ty64anbha.css';
import '../../css/b/b7s7obg4c.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="clr-i-solid clr-i-solid-path-1 vkah-u8kr"/><path class="clr-i-solid clr-i-solid-path-2 h536d422m"/><path class="clr-i-solid clr-i-solid-path-3 ty64anbha"/><path class="b7s7obg4c clr-i-solid clr-i-solid-path-4"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:disconnected-solid" /></template>
