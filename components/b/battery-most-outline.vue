<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icho3y_ph.css';
import '../../css/m/mthptgvbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icho3y_ph"/><path clip-rule="evenodd" class="mthptgvbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:battery-most-outline" /></template>
