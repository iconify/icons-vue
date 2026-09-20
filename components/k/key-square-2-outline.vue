<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mh2suueyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mh2suueyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:key-square-2-outline" /></template>
