<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvwjnacrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lvwjnacrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:hand-left" /></template>
