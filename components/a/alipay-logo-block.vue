<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1-gn6z1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g1-gn6z1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:alipay-logo-block" /></template>
