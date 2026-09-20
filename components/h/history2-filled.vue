<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwrw3lbiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rwrw3lbiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:history2-filled" /></template>
