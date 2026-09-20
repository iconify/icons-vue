<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/al6rhabjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="al6rhabjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:blood-bag-donation-solid" /></template>
