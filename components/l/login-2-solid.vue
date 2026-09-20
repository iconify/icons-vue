<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9oom-12u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n9oom-12u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:login-2-solid" /></template>
