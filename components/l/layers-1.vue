<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4-v4imeh.css';
import '../../css/m/maj_0caaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="c4-v4imeh"/><path class="maj_0caaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:layers-1" /></template>
