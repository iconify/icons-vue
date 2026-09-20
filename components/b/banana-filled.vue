<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzjb0rqzb.css';
import '../../css/m/m99ygkb_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzjb0rqzb"/><path class="m99ygkb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:banana-filled" /></template>
