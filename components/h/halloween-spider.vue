<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/id_uzvtgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="id_uzvtgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:halloween-spider" /></template>
