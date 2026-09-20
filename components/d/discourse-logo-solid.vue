<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxa3xobqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uxa3xobqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:discourse-logo-solid" /></template>
