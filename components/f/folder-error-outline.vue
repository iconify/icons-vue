<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pico9db3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pico9db3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-error-outline" /></template>
