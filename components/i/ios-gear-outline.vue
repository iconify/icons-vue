<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qg-ah_bfc.css';
import '../../css/e/e5ufuhb8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qg-ah_bfc"/><path class="e5ufuhb8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-gear-outline" /></template>
