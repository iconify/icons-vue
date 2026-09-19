<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzlocfotl.css';
import '../../css/k/kx9-9-b3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uzlocfotl"/><path class="kx9-9-b3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-archive" /></template>
