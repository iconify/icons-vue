<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki6tpkbda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ki6tpkbda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:battery-sharp" /></template>
