<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mje02xb7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mje02xb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:kakao-talk-logo-block" /></template>
