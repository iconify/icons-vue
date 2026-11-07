<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7p-8cptj.css';
import '../../css/u/uu8xqrboc.css';
import '../../css/p/pzmtr-buq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7p-8cptj"/><path clip-rule="evenodd" class="uu8xqrboc"/><path clip-rule="evenodd" class="pzmtr-buq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-clock-outline" /></template>
