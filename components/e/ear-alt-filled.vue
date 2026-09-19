<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui0ex75nu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ui0ex75nu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:ear-alt-filled" /></template>
