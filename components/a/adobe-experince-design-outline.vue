<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg9sienad.css';
import '../../css/k/kw60brbej.css';
import '../../css/d/daxtkab1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fg9sienad"/><path class="kw60brbej"/><path clip-rule="evenodd" class="daxtkab1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:adobe-experince-design-outline" /></template>
