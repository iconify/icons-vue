<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqx828nly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cqx828nly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:film-filled" /></template>
