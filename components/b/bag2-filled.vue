<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsop0413d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsop0413d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bag2-filled" /></template>
