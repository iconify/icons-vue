<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wngwu12gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wngwu12gm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:badge-ar-filled" /></template>
