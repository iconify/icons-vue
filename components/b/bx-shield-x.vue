<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7fum4b5a.css';
import '../../css/k/kv4jnr7fz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7fum4b5a"/><path class="kv4jnr7fz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-shield-x" /></template>
