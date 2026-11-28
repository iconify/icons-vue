<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbgmgpb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbgmgpb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:clipboard-list" /></template>
