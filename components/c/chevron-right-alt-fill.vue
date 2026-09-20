<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_nt6zbjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z_nt6zbjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:chevron-right-alt-fill" /></template>
