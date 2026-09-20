<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhextp5nr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-3,"top":-1.5};
const content = `<path class="jhextp5nr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:alien-f" /></template>
