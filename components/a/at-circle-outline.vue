<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv7rk0b4n.css';
import '../../css/i/icd23tbey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rv7rk0b4n"/><path class="icd23tbey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:at-circle-outline" /></template>
