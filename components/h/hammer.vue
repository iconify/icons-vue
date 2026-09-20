<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpa12j_nt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rpa12j_nt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:hammer" /></template>
