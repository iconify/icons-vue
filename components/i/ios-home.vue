<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etxzxd_fz.css';
import '../../css/e/ezvo8ibdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="etxzxd_fz"/><path class="ezvo8ibdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-home" /></template>
