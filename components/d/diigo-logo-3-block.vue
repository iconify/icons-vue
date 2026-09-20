<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-9-kkb6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q-9-kkb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:diigo-logo-3-block" /></template>
