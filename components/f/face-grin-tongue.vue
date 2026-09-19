<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbe25ixpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="nbe25ixpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:face-grin-tongue" /></template>
