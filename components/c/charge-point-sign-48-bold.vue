<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rs_4a5yyu.css';
import '../../css/z/zetb63f3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rs_4a5yyu"/><path class="zetb63f3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charge-point-sign-48-bold" /></template>
