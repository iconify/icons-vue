<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dan12lfgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dan12lfgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:gamebanana" /></template>
