<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fok7ss8hy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fok7ss8hy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:dice-6-horizontal-fill" /></template>
