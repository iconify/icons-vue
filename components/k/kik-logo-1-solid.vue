<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta6jhe_wk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ta6jhe_wk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:kik-logo-1-solid" /></template>
