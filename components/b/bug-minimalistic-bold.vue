<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcq5--p3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zcq5--p3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bug-minimalistic-bold" /></template>
