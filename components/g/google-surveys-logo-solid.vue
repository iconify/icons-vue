<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eoha7p_ju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eoha7p_ju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-surveys-logo-solid" /></template>
