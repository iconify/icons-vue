<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m16zfhb7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m16zfhb7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:intestine-24px" /></template>
