<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztcz48ldh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ztcz48ldh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:battery-most-solid" /></template>
