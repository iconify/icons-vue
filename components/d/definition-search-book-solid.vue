<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phft6lxqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="phft6lxqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:definition-search-book-solid" /></template>
