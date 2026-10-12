<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6mxce4uq.css';
import '../../css/n/nuwhiyu0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6mxce4uq"/><path class="nuwhiyu0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:heart-handshake-filled" /></template>
