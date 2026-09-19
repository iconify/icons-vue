<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egh3qukbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="egh3qukbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:info-circle-solid" /></template>
