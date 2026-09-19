<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9e_ecbxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y9e_ecbxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chart-appearance-alt-filled" /></template>
