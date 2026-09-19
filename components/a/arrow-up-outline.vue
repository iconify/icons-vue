<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldmnugbgt.css';
import '../../css/a/aqgm4tbwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ldmnugbgt"/><path clip-rule="evenodd" class="aqgm4tbwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:arrow-up-outline" /></template>
