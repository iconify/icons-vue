<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1zokhhls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1zokhhls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:controller-device-safety" /></template>
