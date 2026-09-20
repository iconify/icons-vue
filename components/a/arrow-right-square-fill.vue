<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovmqfnq7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ovmqfnq7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:arrow-right-square-fill" /></template>
