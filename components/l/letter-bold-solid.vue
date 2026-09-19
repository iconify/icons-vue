<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvu-1-bhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xvu-1-bhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:letter-bold-solid" /></template>
