<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq6ilubpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fq6ilubpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:battery-half" /></template>
