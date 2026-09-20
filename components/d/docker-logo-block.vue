<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asn3kcb6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="asn3kcb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:docker-logo-block" /></template>
