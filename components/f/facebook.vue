<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcjva0oju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xcjva0oju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:facebook" /></template>
