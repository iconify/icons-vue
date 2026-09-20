<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b14kaei-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b14kaei-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:check-circle-fill" /></template>
