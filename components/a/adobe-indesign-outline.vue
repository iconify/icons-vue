<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gux5og_2t.css';
import '../../css/m/mjz1r4_dm.css';
import '../../css/d/daxtkab1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gux5og_2t"/><path class="mjz1r4_dm"/><path clip-rule="evenodd" class="daxtkab1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:adobe-indesign-outline" /></template>
