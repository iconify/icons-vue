<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9kmf9bcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9kmf9bcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:ball" /></template>
