<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9m55n4ik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9m55n4ik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:end-call-linear" /></template>
