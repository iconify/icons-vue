<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cut31abpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cut31abpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:eye-off-fill" /></template>
