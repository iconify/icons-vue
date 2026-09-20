<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9w90ebru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y9w90ebru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-10-sharp-fill" /></template>
