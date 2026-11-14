<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhkmyz5ha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhkmyz5ha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:diamond-plus" /></template>
