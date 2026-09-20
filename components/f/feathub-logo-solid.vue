<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae1bp_7og.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ae1bp_7og"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:feathub-logo-solid" /></template>
