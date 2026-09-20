<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh6d9rdxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gh6d9rdxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:bugsnag-logo-solid" /></template>
