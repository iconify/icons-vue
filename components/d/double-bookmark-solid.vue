<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj-wffr9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nj-wffr9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:double-bookmark-solid" /></template>
