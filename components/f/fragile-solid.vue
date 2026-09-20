<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a42s6sbrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a42s6sbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:fragile-solid" /></template>
