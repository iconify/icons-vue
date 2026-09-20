<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_vtj1bpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l_vtj1bpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:logmein-logo-2-solid" /></template>
