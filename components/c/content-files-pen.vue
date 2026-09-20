<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps9lkiisw.css';
import '../../css/o/oh5vljisv.css';
import '../../css/r/rlcxgmb1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ps9lkiisw"/><path class="oh5vljisv"/><path class="rlcxgmb1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:content-files-pen" /></template>
