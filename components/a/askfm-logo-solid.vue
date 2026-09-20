<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds3z54bye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ds3z54bye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:askfm-logo-solid" /></template>
