<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzlanurfx.css';
import '../../css/x/x5igzyszp.css';
import '../../css/z/zwpgspbzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dzlanurfx"/><path class="x5igzyszp"/><path class="zwpgspbzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-recovery-48-bold" /></template>
