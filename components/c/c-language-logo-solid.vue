<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7wjqvbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q7wjqvbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:c-language-logo-solid" /></template>
