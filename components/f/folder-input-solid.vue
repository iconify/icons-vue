<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca_bn4ekm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ca_bn4ekm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:folder-input-solid" /></template>
