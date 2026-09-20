<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szenc4b2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="szenc4b2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:leaf-1" /></template>
