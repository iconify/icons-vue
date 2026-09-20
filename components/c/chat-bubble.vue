<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rls_dv.css';
import '../../css/s/so-from-70.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rls_dv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:chat-bubble" /></template>
