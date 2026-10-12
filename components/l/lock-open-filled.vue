<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oci9svhqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oci9svhqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:lock-open-filled" /></template>
