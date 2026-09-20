<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-1-n-cnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-1-n-cnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:dice-2" /></template>
