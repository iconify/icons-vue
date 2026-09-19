<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgr579nhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgr579nhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:lock-closed" /></template>
