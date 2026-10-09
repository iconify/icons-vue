<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okzvs_blx.css';
import '../../css/g/gu1a-jb1z.css';
import '../../css/t/tvwqtv2ki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="okzvs_blx"/><path class="gu1a-jb1z"/><path class="tvwqtv2ki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lock-keyhole-20" /></template>
