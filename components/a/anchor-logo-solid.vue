<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iedmqkb3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iedmqkb3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:anchor-logo-solid" /></template>
