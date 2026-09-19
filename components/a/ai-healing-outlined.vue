<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3b7b6biu.css';
import '../../css/d/d79oyzb2x.css';
import '../../css/d/d1ym2h3ya.css';
import '../../css/d/d9tmbcbad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3b7b6biu"/><circle class="d79oyzb2x"/><circle class="d1ym2h3ya"/><path class="d9tmbcbad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:ai-healing-outlined" /></template>
