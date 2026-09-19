<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0ldy-bsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="l0ldy-bsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:bikeshed" /></template>
