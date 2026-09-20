<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpkt9abpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpkt9abpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:heart" /></template>
