<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3s7nok3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u3s7nok3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:cloudsmith-logo-block" /></template>
