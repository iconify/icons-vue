<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0z666bnz.css';
import '../../css/l/l2skeeb_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0z666bnz"/><path class="l2skeeb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:duplicate" /></template>
