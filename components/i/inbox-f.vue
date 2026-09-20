<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/begzp6bby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-5};
const content = `<path class="begzp6bby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:inbox-f" /></template>
