<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjnc-d4pe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="yjnc-d4pe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:dots-2x2-20-solid" /></template>
