<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxb7bva-l.css';
import '../../css/m/m6c-bbbaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxb7bva-l"/><path class="m6c-bbbaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bolt" /></template>
