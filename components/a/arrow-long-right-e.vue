<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/buwjnd3lz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="buwjnd3lz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:arrow-long-right-e" /></template>
