<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/actx8vb0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="actx8vb0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:dcb" /></template>
