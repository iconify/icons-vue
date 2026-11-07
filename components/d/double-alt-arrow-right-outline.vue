<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydc0e7axo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ydc0e7axo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:double-alt-arrow-right-outline" /></template>
