<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm59sjb2h.css';
import '../../css/s/sn9k1h9dt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dm59sjb2h"/><path class="sn9k1h9dt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:chart-line" /></template>
