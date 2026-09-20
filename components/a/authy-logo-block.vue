<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojt3_9lvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ojt3_9lvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:authy-logo-block" /></template>
