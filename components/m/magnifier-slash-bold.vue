<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa6kukbpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xa6kukbpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magnifier-slash-bold" /></template>
