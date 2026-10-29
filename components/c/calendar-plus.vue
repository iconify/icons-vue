<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehoar8bab.css';
import '../../css/t/t95kfgwfc.css';
import '../../css/s/spenj8_cl.css';
import '../../css/b/b_l2oflil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehoar8bab wm-k"/><path class="t95kfgwfc wm-k"/><path class="spenj8_cl wm-a"/><path class="b_l2oflil wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:calendar-plus" /></template>
