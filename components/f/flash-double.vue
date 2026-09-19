<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfbn_4p6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mfbn_4p6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:flash-double" /></template>
