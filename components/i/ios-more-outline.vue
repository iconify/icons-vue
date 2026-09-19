<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwyxrkbgu.css';
import '../../css/e/ec9sckbjq.css';
import '../../css/g/grxa6ebnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cwyxrkbgu"/><path class="ec9sckbjq"/><path class="grxa6ebnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-more-outline" /></template>
