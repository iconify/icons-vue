<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyrsscxbi.css';
import '../../css/p/pha2jnncv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uyrsscxbi"/><path class="pha2jnncv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:insur" /></template>
