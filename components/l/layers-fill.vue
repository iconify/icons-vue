<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdkgnbbwr.css';
import '../../css/l/lcfo21bnz.css';
import '../../css/k/kfdgnyb-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdkgnbbwr"/><path clip-rule="evenodd" class="lcfo21bnz"/><path clip-rule="evenodd" class="kfdgnyb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:layers-fill" /></template>
