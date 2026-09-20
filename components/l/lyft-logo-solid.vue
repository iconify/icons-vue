<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm22fiowk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hm22fiowk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:lyft-logo-solid" /></template>
