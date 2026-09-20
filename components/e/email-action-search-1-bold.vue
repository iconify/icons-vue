<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbx4p_6nb.css';
import '../../css/l/l4ej3fvuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbx4p_6nb"/><path class="l4ej3fvuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:email-action-search-1-bold" /></template>
