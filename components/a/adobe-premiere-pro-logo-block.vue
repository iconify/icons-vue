<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3kr0dbyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k3kr0dbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:adobe-premiere-pro-logo-block" /></template>
