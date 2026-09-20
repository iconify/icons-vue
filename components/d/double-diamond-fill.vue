<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkgj8db4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkgj8db4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:double-diamond-fill" /></template>
