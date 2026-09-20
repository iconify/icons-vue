<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chhvm5r4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="chhvm5r4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:gallery2-filled" /></template>
