<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l20sm2b8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l20sm2b8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:cart-add-solid" /></template>
