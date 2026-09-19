<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjpbc1c8o.css';
import '../../css/m/mthptgvbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjpbc1c8o"/><path clip-rule="evenodd" class="mthptgvbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:battery-full-outline" /></template>
