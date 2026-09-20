<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/z/zkv446btt.css';
import '../../css/w/wxt4s-b2x.css';
import '../../css/n/nk6_eibzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="zkv446btt"/><path class="wxt4s-b2x"/><path class="nk6_eibzl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:keyboard-wireless-2-flat" /></template>
