<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4428xb7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r4428xb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:key2-filled" /></template>
