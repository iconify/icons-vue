<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syehdcb-y.css';
import '../../css/l/lv_77yb9s.css';
import '../../css/c/ceo0kmpvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="syehdcb-y wm-a"/><path class="lv_77yb9s wm-a"/><path class="ceo0kmpvt wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:cloud-sun" /></template>
