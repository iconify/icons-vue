<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6dze1_pf.css';
import '../../css/v/ved-39bzt.css';
import '../../css/q/qiprivbld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d6dze1_pf"/><path class="ved-39bzt"/><path class="qiprivbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:bonfire-outline" /></template>
