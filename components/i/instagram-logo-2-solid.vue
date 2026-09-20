<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzk1px2nz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hzk1px2nz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:instagram-logo-2-solid" /></template>
