<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvk4ocgpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvk4ocgpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:arrow-circle-up-right" /></template>
