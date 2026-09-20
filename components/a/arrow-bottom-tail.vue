<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bluom-brx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bluom-brx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-bottom-tail" /></template>
