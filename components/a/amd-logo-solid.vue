<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg1e5gzxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gg1e5gzxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:amd-logo-solid" /></template>
