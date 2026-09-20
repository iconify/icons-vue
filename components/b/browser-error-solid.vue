<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5xly1btp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b5xly1btp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:browser-error-solid" /></template>
