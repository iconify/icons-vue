<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhh9m-5ks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yhh9m-5ks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-home-logo-solid" /></template>
