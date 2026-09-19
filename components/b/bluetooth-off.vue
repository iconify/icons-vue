<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcdy78bcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pcdy78bcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:bluetooth-off" /></template>
