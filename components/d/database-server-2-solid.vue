<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abpo0gboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="abpo0gboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:database-server-2-solid" /></template>
