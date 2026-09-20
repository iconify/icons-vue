<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv2h5uisl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv2h5uisl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:leaf" /></template>
