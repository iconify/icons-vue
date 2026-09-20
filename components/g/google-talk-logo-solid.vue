<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu0nlzj2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mu0nlzj2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-talk-logo-solid" /></template>
