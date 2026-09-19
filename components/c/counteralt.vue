<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7i3mcv0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":768};
const content = `<path class="p7i3mcv0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:counteralt" /></template>
