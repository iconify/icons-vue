<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0jg6ub4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c0jg6ub4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:codepen-logo-solid" /></template>
