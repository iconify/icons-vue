<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz183ibfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz183ibfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:flask" /></template>
