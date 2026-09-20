<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbk_2kbbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cbk_2kbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:close-round-fill" /></template>
