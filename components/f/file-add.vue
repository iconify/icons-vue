<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue5dmkb5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ue5dmkb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:file-add" /></template>
