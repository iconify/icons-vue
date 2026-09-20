<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avdx2ebrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="avdx2ebrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:livejournal-logo-block" /></template>
