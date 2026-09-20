<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxg7tg66d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gxg7tg66d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:affinity-publiser-logo-solid" /></template>
