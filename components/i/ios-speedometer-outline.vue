<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bas7btrby.css';
import '../../css/x/x7m723b_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bas7btrby"/><path class="x7m723b_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-speedometer-outline" /></template>
