<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk_c8jfkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sk_c8jfkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:lock-fill" /></template>
