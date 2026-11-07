<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_hf_9u3p.css';
import '../../css/a/autb8mb3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_hf_9u3p"/><path class="autb8mb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:call-dropped-bold" /></template>
