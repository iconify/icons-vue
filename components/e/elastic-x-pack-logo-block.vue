<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il0odlseg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="il0odlseg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:elastic-x-pack-logo-block" /></template>
