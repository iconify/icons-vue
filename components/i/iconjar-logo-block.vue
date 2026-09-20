<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x__ihteae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x__ihteae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:iconjar-logo-block" /></template>
