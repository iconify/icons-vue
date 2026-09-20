<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufsopbbuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="ufsopbbuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:headset-f" /></template>
