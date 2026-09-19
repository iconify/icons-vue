<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdf4g625i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdf4g625i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:dialpad" /></template>
